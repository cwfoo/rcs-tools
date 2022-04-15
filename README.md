# RCS tools
Additional scripts for RCS (Revision Control System).


## Scripts
### `rcsamend`
Edit an RCS log message in a text editor. This is a user-friendly alternative to
`rcs -m...`. Inspired by `git commit --amend ...`.

### `rcstag`
Similar to `rcsfreeze`, but only files in the working directory (i.e. checked
out files) are given new symbolic names. Useful for managing multi-file projects
where some files are renamed or no longer needed ("deleted"). Inspired by
`git tag ...`.

Credits: `rcstag` is modified from `rcsfreeze` obtained from GNU RCS 5.10.0
(released: 2020-10-20).


## Installation
Copy or symbolically link the scripts into a directory on your `PATH`.
e.g. `cp rcstag ~/bin/.` or `ln -s "$(pwd)/rcstag" ~/bin/.`


## Usage
Each script has a `--help` option that prints usage information.


## License
GPLv3 or (at your option) any later version.


## Contributing
Bug reports, suggestions, and patches should be submitted on GitHub:
https://github.com/cwfoo/rcs-tools


## Other useful tools
You may also be interested in these tools:
* [rcsi](https://web.archive.org/web/20160331000703/http://www.colinbrough.pwp.blueyonder.co.uk/rcsi.README.html) —
    Displays the status of RCS files in a directory. Analogous to `git status`.
