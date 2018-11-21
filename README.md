# JSword-tweaks

jsword-tweaks is used to build jsword.jar for And Bible.

# Preparations

First make sure that your directory structure is such that
you have your repositories like this:


```
# JSword from https://github.com/AndBible/jsword
jsword 
# Main And Bible repository https://github.com/AndBible/and-bible
and-bible/and-bible
# This repository
and-bible/jsword-tweaks
```

You need to install ant:

```
sudo apt install ant
```


# How does it work?

It first installs some dependencies (ivy)
copies java files from jsword, appends some
java files from this repository, and builds
jar file.

# How to build jsword.jar?

Run 

```
ant
```

in jsword-tweaks folder, and it will
build jsword.jar and jsword-src.jar, and copy
them into And Bible repository.
