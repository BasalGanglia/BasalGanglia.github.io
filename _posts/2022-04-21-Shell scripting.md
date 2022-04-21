---
layout: post
title: Shell scripting self-study
author: User
summary: Summary of the article
---

```bash
#!/bin/bash # shebang!

if [[ "${1}" = start]] # old school

case "{$1}" in
    start)
        echo 'start'
        ;;
    stop)
        echo 'stop'
        ;;
    status|state) # or with |
        echo 'status'
        ;;
    *)
        echo 'give something real.' >&2 # to stderr
        exit 1 # non 0 exit status
        ;;
esac
```