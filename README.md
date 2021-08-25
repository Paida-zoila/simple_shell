# Simple Shell

A simple UNIX shell written in C.

# Compile

To compile, run `make`. Alternatively, use the full compilation command:

```
gcc -Wall -Werror -Wextra -pedantic *.c -o shell
```

# Running

To run, use `./shell` in the same way you would use `bash`.

## Example 1:

```
root@e8fdb802c28a:~/simple_shell#./shell
# ls
shell
# ls -alh
total 140K

drwxr-xr-x 5 root root 4.0K Aug 25 11:22 .

drwx------ 1 root root  198 Aug 25 11:13 ..

-rwxr-xr-x 1 root root  265 Aug 25 11:11 atoi.c

-rw-r--r-- 1 root root  272 Aug 25 11:11 AUTHORS

-rwxr-xr-x 1 root root  879 Aug 25 11:11 debug.c

-rwxr-xr-x 1 root root  507 Aug 25 11:11 env.c

-rwxr-xr-x 1 root root  178 Aug 25 11:11 exit.c

-rwxr-xr-x 1 root root  195 Aug 25 11:11 free.c

-rwxr-xr-x 1 root root 2.2K Aug 25 11:11 get_fpath.c

drwxr-xr-x 8 root root  163 Aug 25 11:21 .git

-rwxr-xr-x 1 root root  960 Aug 25 11:11 handle_builtins.c

-rwxr-xr-x 1 root root  167 Aug 25 11:11 handle_comments.c

-rwxr-xr-x 1 root root 1.5K Aug 25 11:11 handle_exec.c

-rw-r--r-- 1 root root 2.3K Aug 25 11:11 header.h

-rwxr-xr-x 1 root root  295 Aug 25 11:11 help.c

-rwxr-xr-x 1 root root  284 Aug 25 11:11 interactive.c

-rwxr-xr-x 1 root root 1.4K Aug 25 11:11 main.c

-rw-r--r-- 1 root root  269 Aug 25 11:11 Makefile

-rw-r--r-- 1 root root  404 Aug 25 11:21 man_1_simple_shell

-rwxr-xr-x 1 root root  760 Aug 25 11:11 new_path_string.c

-rwxr-xr-x 1 root root   75 Aug 25 11:11 print_char.c

-rwxr-xr-x 1 root root  327 Aug 25 11:11 print_func.c

-rwxr-xr-x 1 root root  149 Aug 25 11:11 print_grid.c

-rwxr-xr-x 1 root root  162 Aug 25 11:11 print_prompt.c

lrwxrwxrwx 1 root root   21 Aug 25 11:22 .#README.md -> root@759315590b02.237

-rw-r--r-- 1 root root  851 Aug 25 10:55 README.md

-rwxr-xr-x 1 root root 2.0K Aug 25 11:11 setenv.c

-rwxr-xr-x 1 root root  24K Aug 25 11:22 shell

-rwxr-xr-x 1 root root  122 Aug 25 11:11 signal.c

-rwxr-xr-x 1 root root 1.5K Aug 25 11:11 string2.c

-rwxr-xr-x 1 root root 1.6K Aug 25 11:11 string.c

-rwxr-xr-x 1 root root  115 Aug 25 11:11 strip_newline.c

drwxr-xr-x 2 root root  103 Aug 25 11:11 tests

drwxr-xr-x 2 root root   26 Aug 25 11:11 trash

-rwxr-xr-x 1 root root 1.2K Aug 25 11:11 unsetenv.c  
```

## Example 2:
```
root@e8fdb802c28a:~/simple_shell# ./shell
# ls
shell
# ls -alh
total 144K

drwxr-xr-x 5 root root 4.0K Aug 25 11:23  .

drwx------ 1 root root  219 Aug 25 11:26  ..

-rwxr-xr-x 1 root root  265 Aug 25 11:11  atoi.c

-rw-r--r-- 1 root root  272 Aug 25 11:11  AUTHORS

-rwxr-xr-x 1 root root  879 Aug 25 11:11  debug.c

-rwxr-xr-x 1 root root  507 Aug 25 11:11  env.c

-rwxr-xr-x 1 root root  178 Aug 25 11:11  exit.c

-rwxr-xr-x 1 root root  195 Aug 25 11:11  free.c

-rwxr-xr-x 1 root root 2.2K Aug 25 11:11  get_fpath.c

drwxr-xr-x 8 root root  163 Aug 25 11:21  .git

-rwxr-xr-x 1 root root  960 Aug 25 11:11  handle_builtins.c

-rwxr-xr-x 1 root root  167 Aug 25 11:11  handle_comments.c

-rwxr-xr-x 1 root root 1.5K Aug 25 11:11  handle_exec.c

-rw-r--r-- 1 root root 2.3K Aug 25 11:11  header.h

-rwxr-xr-x 1 root root  295 Aug 25 11:11  help.c

-rwxr-xr-x 1 root root  284 Aug 25 11:11  interactive.c

-rwxr-xr-x 1 root root 1.4K Aug 25 11:11  main.c

-rw-r--r-- 1 root root  269 Aug 25 11:11  Makefile

-rw-r--r-- 1 root root  404 Aug 25 11:21  man_1_simple_shell

-rwxr-xr-x 1 root root  760 Aug 25 11:11  new_path_string.c

-rwxr-xr-x 1 root root   75 Aug 25 11:11  print_char.c

-rwxr-xr-x 1 root root  327 Aug 25 11:11  print_func.c

-rwxr-xr-x 1 root root  149 Aug 25 11:11  print_grid.c

-rwxr-xr-x 1 root root  162 Aug 25 11:11  print_prompt.c

-rw-r--r-- 1 root root 2.4K Aug 25 11:28 '#README.md#'

lrwxrwxrwx 1 root root   21 Aug 25 11:22  .#README.md -> root@759315590b02.237

-rw-r--r-- 1 root root  851 Aug 25 10:55  README.md

-rwxr-xr-x 1 root root 2.0K Aug 25 11:11  setenv.c

-rwxr-xr-x 1 root root  24K Aug 25 11:22  shell

-rwxr-xr-x 1 root root  122 Aug 25 11:11  signal.c

-rwxr-xr-x 1 root root 1.5K Aug 25 11:11  string2.c

-rwxr-xr-x 1 root root 1.6K Aug 25 11:11  string.c

-rwxr-xr-x 1 root root  115 Aug 25 11:11  strip_newline.c

drwxr-xr-x 2 root root  103 Aug 25 11:11  tests

drwxr-xr-x 2 root root   26 Aug 25 11:11  trash

-rwxr-xr-x 1 root root 1.2K Aug 25 11:11  unsetenv.c
# exit 98
root@e8fdb802c28a:~/simple_shell# echo $?
98
root@e8fdb802c28a:~/simple_shell#
```