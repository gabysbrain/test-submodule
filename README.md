
This is an example using [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

This is kind of the header doc to the whole set of repos. You can add a link
here to the index of the documentation/diary like so:

* [code1](code1/README.md)
* [code2](code2/README.md)

However, these links will only work on the local drive. It doesn't look like
this can be easily mapped without some scripting. Maybe
https://docs.github.com/en/github/writing-on-github/autolinked-references-and-urls
can help?

The child repos can be developed independently of this one. 

The issue with git submodules is that the repo references here won't 
automatically update when people push to the submodules.

People will ideally need permissions for this catchall repository as well as
the particular module they are developing.

There doesn't seem to be a way to only include a particular subdirectory
of one of the submodules in this one.

