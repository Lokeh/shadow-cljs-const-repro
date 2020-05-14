This repo is a minimal reproduction of an error introduced in shadow-cljs 2.8.95.

Editing a depenency of a namespace which defines a `^:const` var results in
build failures. Editing the namespace again, resolves the issue.
