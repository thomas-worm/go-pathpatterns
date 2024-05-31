# go-pathpatterns

The `go-pathpatterns` module helps parsing the commonly used path patterns by Go developers, e.g. the `./...` pattern for recursive traversal.

## Possible Patterns

The patterns consist of the following main possibilities.

### Lists

You can merge the set of matched files from multiple path patterns by combining them with comma.

Here are some examples:

* `one.txt,two.txt`
* `src/app/*.vue,src/app/*.css`

### Directory Traversals

You can use the well-known `.` for the current directory and `..` for the parent directory.  
For recursive traversal into child directories, you can use `...`.

So for example `./...` will traverse through all child directories of the current directory.

### Wildcards

You can use the wildcard character `*` to match all paths with zero to any length string in the place of the wildcard.


