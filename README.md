Functionality:
download both files

RUN:
```bash
chmod +x ishmonkey
```
 FOR GENERAL USE:
 Replace init with the command and arguments/flags
 Use git documentation https://git-scm.com/doc

```bash
./ishmonkey init
```


This is a local git clone, that functions with the standard functions of:

- `case "add"          : cmd_add(args)`
- `case "cat-file"     : cmd_cat_file(args)`
- `case "check-ignore" : cmd_check_ignore(args)`
- `case "checkout"     : cmd_checkout(args)`
- `case "commit"       : cmd_commit(args)`
- `case "hash-object"  : cmd_hash_object(args)`
- `case "init"         : cmd_init(args)`
- `case "log"          : cmd_log(args)`
- `case "ls-files"     : cmd_ls_files(args)`
- `case "ls-tree"      : cmd_ls_tree(args)`
- `case "rev-parse"    : cmd_rev_parse(args)`
- `case "rm"           : cmd_rm(args)`
- `case "show-ref"     : cmd_show_ref(args)`
- `case "status"       : cmd_status(args)`
- `case "tag"          : cmd_tag(args)`
- `case _`



  Learnt alot making this and it tecahes alot about objects and 
  how git works in general, doesnt work well with symlinks and also needs
  some fixing in certain cases
  eg doesnt do well with empty repositiories

  Enjoy my comments, they were to help me understand what the hell is going on
  
   USED: https://wyag.thb.lt/#orge9fef61
   incredinly hepful
   may come back to port with HTTP and connect to github 
   
  
