# abhi2
C:\Users\admin>cd C:\ai59\gitlab\exp1

C:\ai59\gitlab\exp1>git init
Reinitialized existing Git repository in C:/ai59/gitlab/exp1/.git/

C:\ai59\gitlab\exp1>cd C:\ai59\gitlab\exp2

C:\ai59\gitlab\exp2>git init
Initialized empty Git repository in C:/ai59/gitlab/exp2/.git/

C:\ai59\gitlab\exp2>git add fil2.txt

C:\ai59\gitlab\exp2>git commit -m
error: switch `m' requires a value

C:\ai59\gitlab\exp2>git commit -m "mess1"
[master (root-commit) c3e0a53] mess1
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fil2.txt

C:\ai59\gitlab\exp2>git log
commit c3e0a530b5405c066ee144a897e9968b5cf4ecb4 (HEAD -> master)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Fri Mar 8 20:46:11 2024 +0530

    mess1

C:\ai59\gitlab\exp2>git checkout -b fj
Switched to a new branch 'fj'

C:\ai59\gitlab\exp2>git add fil2.txt

C:\ai59\gitlab\exp2>git commit -m "mess1"
[fj 0718d12] mess1
 1 file changed, 1 insertion(+)

C:\ai59\gitlab\exp2>git log
commit 0718d123a83790a4ae14fdc8811b53626bf413b9 (HEAD -> fj)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Fri Mar 8 20:48:10 2024 +0530

    mess1

commit c3e0a530b5405c066ee144a897e9968b5cf4ecb4 (master)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Fri Mar 8 20:46:11 2024 +0530

    mess1

C:\ai59\gitlab\exp2>git stash save "messag2"
No local changes to save

C:\ai59\gitlab\exp2>git stash save "messag2"
Saved working directory and index state On fj: messag2

C:\ai59\gitlab\exp2>git checkout -b fj
fatal: a branch named 'fj' already exists

C:\ai59\gitlab\exp2>git checkout -b fjk
Switched to a new branch 'fjk'

C:\ai59\gitlab\exp2>git stash apply
On branch fjk
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   fil2.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\ai59\gitlab\exp2>git add fil2.txt

C:\ai59\gitlab\exp2>git commit -m "mess1"
[fjk d658869] mess1
 1 file changed, 1 insertion(+)

C:\ai59\gitlab\exp2>git stash apply
On branch fjk
nothing to commit, working tree clean

C:\ai59\gitlab\exp2>git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --[no-]verbose    be more verbose
    -q, --[no-]quiet      be more quiet
    --[no-]progress       force progress reporting
    --[no-]reject-shallow don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --checkout            opposite of --no-checkout
    --[no-]bare           create a bare repository
    --[no-]mirror         create a mirror repository (implies bare)
    -l, --[no-]local      to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    --hardlinks           opposite of --no-hardlinks
    -s, --[no-]shared     setup as shared repository
    --[no-]recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --[no-]recursive ...  alias of --recurse-submodules
    -j, --[no-]jobs <n>   number of submodules cloned in parallel
    --[no-]template <template-directory>
                          directory from which templates will be used
    --[no-]reference <repo>
                          reference repository
    --[no-]reference-if-able <repo>
                          reference repository
    --[no-]dissociate     use --reference only while cloning
    -o, --[no-]origin <name>
                          use <name> instead of 'origin' to track upstream
    -b, --[no-]branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --[no-]upload-pack <path>
                          path to git-upload-pack on the remote
    --[no-]depth <depth>  create a shallow clone of that depth
    --[no-]shallow-since <time>
                          create a shallow clone since a specific time
    --[no-]shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --[no-]single-branch  clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --tags                opposite of --no-tags
    --[no-]shallow-submodules
                          any cloned submodules will be shallow
    --[no-]separate-git-dir <gitdir>
                          separate git dir from working tree
    --[no-]ref-format <format>
                          specify the reference format to use
    -c, --[no-]config <key=value>
                          set config inside the new repository
    --[no-]server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --[no-]filter <args>  object filtering
    --[no-]also-filter-submodules
                          apply partial clone filters to submodules
    --[no-]remote-submodules
                          any cloned submodules will use their remote-tracking branch
    --[no-]sparse         initialize sparse-checkout file to include only files at root
    --[no-]bundle-uri <uri>
                          a URI for downloading bundles before fetching from origin remote


C:\ai59\gitlab\exp2>git clone https://github.com/suraj-6/new-world-.git
Cloning into 'new-world-'...
warning: You appear to have cloned an empty repository.

C:\ai59\gitlab\exp2>
