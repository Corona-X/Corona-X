#Corona-X
Corona-X Project Manifest

#Building[^1]

Building Corona-X requires a bourne-like shell (`bash`, `sh`, etc.), google `repo`, and a working (native) C Compiler.
`repo` can be downloaded with the following command: `curl https://storage.googleapis.com/git-repo-downloads/repo > repo`[2^]

##Instructions to Check Out the Source Tree:

1. Make a folder to store the source

2. Open a shell and navigate to the folder from step 1 (`cd name`)

4. Execute `repo init -u https://github.com/Corona-X/Corona-X -b branch`[^3] in the source folder.

5. Execute `repo sync`. This will download the current Corona-X source tree.

##Instructions for Building the Source Tree:



[^1]: Corona-X will build on Mac OS X, most Linux Distributions, and (soon!) itself
[^2]: See [here](https://code.google.com/p/git-repo/) or [here](http://source.android.com/source/downloading.html) for more information on installing and using repo
[^3]: Current Branches: `Initial-Development`
