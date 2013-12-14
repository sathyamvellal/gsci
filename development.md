GSCI :: Development Procedure
==============================

The project's source code will be available in [http://github.com/pesos/gsci][1]. 

### For newcomers

1. Please go through the [references document][2]. This has information regarding what you'd need to know to contribute to this project.
2. For any queries, you can [mail me](mailto:mail@sathyam.me). You can also reach [me in facebook](http://sathyamvellal.in/fb).

---

### Development Procedure

As a contributor to this project you are required to follow this development procedure. This makes it easy for collaboration as many developers would be working together.

#### Initializing Development

+ You must use git for version controlling and github for maintaining the remote repo.
+ You must develop on a branch named **dev** and not in the master branch.

#### Merging Changes

+ When your commits are matured to be patched, you send a pull request in the [official repo][1]; you are still in the dev branch.
+ These changes will be reviewed and merged into the **dev** branch of the main repo. Once these changes are mature enough to add a significant functionality to the tool, it'll be merged into the master branch by the maintainer. 

#### Issue maintanance

+ All bugs will be reported in main repo in the [issues section][3].
+ A contributor will be assigned to work on the bugfix. The contributor will create a new branch in their remote repo with the name **bugfix_#IssueNumber** and work to fix the bug on that branch, unless its a minor bug which can be fixed on the **dev** branch directly.
+ Once this is done, a pull request will be sent by the assigned contibutor for the same. 

---

For all discussions we'll be using using the mailing list. Note that you must prepend the subject with "[projects] [gsci]" tags to mark that thread as a discussion for the gsci project.  

[1]: https://github.com/pesos/gsci
[2]: https://github.com/sathyamvellal/gsci/tree/design/references.md
[3]: https://github.com/pesos/gsci/issues
