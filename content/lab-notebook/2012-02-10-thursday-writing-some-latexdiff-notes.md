---
categories:
- ecology
comments: true
date: 2012-02-10T10:06:11Z
redirects:
- /wordpress/archives/3804
- /archives/3804
slug: thursday-writing-some-latexdiff-notes
tags:
- code-tricks
title: 'Thursday: writing; some latexdiff notes'
url: /2012/02/10/thursday-writing-some-latexdiff-notes/
---

## Forage fish writing

See doc, FF dropbox PopDyn



## Warning signals edits

* Alan edits
* Figure captions, titles.  
* Text changes from Noam.  



## A better git latexdiff solution


Placing the script below somewhere in the path like `/usr/local/bin` and modify `~/.gitconfig` as indicated in the header comments.  Then oen can view pdf-diffs of the latex of the current version against previous versions with commands such as

```bash
git latexdiff HEAD 
```

shows the differences between the last commit and the current (uncommitted) changes.  References to other versions should work just as in git diff commands, see [git book for more](http://book.git-scm.com/3_comparing_commits_-_git_diff.html).  


[gist id=1128616]


##  logistics 

* Evolution reimbursement.  
* CPB travel funds.  





