# tailon

Log-Directory:  /log

Run Example: `docker run -d --name tailon -v /path/to/log/dir:/log port22/tailon *`

the `*` at the end is the argument passed to the tailon binary. It must not contain spaces.  
  It can be a file or globbed like `error.log{.*}`
