# Awesome VCS tools
A curated list of awesome Version control tools - clients, diffs etc.

Please, contribute!

# Desktop clients

## Git

[Git](https://git-scm.com/) - most popular decentralized version control system.

### Docs

* [Git magic book](http://www-cs-students.stanford.edu/~blynn/gitmagic/) by Ben Lynn.
* [Pro Git book](https://git-scm.com/book) by Scott Chacon and Ben Straub.
* [Git How to](https://githowto.com/) - a guided tour that walks through the fundamentals of Git.
* [Git Cheatsheet](http://ndpsoftware.com/git-cheatsheet.html) - Git Cheatsheet from NDP software.
* [Git Immersion](http://gitimmersion.com/) - is a guided tour that walks through the fundamentals of Git.

### Clients

* [GitHub Desktop](https://desktop.github.com/) - official GitHub client.
* [SmartGit](http://www.syntevo.com/smartgit/) - stand-alone or portable Git client.
* [TortoiseGit](https://tortoisegit.org/) - Windows Explorer shell extension.
* [GitKraken](https://www.gitkraken.com)
* [Git Extensions](http://gitextensions.github.io/) - Windows Explorer extension.
* [Legit](http://www.git-legit.org/) - command-line interface for Git, optimized for workflow simplicity.

### Client extensions

* [Turbo Git](https://github.com/labs-js/turbo-git) - commit convention support.
* [Magit](https://github.com/magit/magit) - A Git Porcelain inside Emacs.
* [gitforge](https://github.com/nhorman/gitforge)  Utility for manipulating git forges.
* [forge-cli](https://github.com/remolueoend/forge-cli)  cLI for editing and creating issues and merge requests on Gitlab, github and others.

### GitHub extensions

* [Renders TeXy Math for Github readme and commit](https://github.com/leegao/readme2tex).

### Behind GitHub

* [GitHub Engineering - The Blog of the GitHub Engineering Team](https://githubengineering.com).
* http://githut.info/ - GitHub language statistics
* [Git.io](https://git.io/) - GitHub links shortened
* [GitHub Archive](https://www.githubarchive.org/) - GitHub statistics

### Mods

* [Git Virtual File System](https://github.com/Microsoft/gvfs), and [and some back story](https://blogs.msdn.microsoft.com/bharry/2017/02/03/scaling-git-and-some-back-story/)

### Extras

`gitignore` is a rules for Git working copy.
* [github/gitignore](https://github.com/github/gitignore) - a collection of .gitignore templates
* [gitignore.io](https://www.gitignore.io/) - create useful .gitignore Files For Your Project

## SVN

[SVN](http://subversion.apache.org/) - popular centralized version control system.

### Docs

* [SVN Red book](http://svnbook.red-bean.com/) - you should to start here.

### Clients

* [TortoiseSVN](https://tortoisesvn.net/)  - Windows Explorer shell extension
* [Version Control for engineers](http://soft.postpdm.com/)

## Mercurial

* [SmartHG](http://www.syntevo.com/smartgit/) - stand-alone or portable Git client
* [TortoiseHg](http://tortoisehg.bitbucket.org/) - Windows Explorer shell extension

# Stand-alone diff tools

## Text diff

* KDiff https://sourceforge.net/projects/kdiff3
* WinDiff https://en.wikipedia.org/wiki/WinDiff
* [WinMerge](https://sourceforge.net/projects/winmerge) - compare and merge text files
* ccdiff https://sourceforge.net/projects/ccdiff
* DiffEngineX https://en.wikipedia.org/wiki/DiffEngineX
* Diff-Text https://en.wikipedia.org/wiki/Diff-Text
* Pretty Diff https://en.wikipedia.org/wiki/Pretty_Diff
* ExamDiff http://www.prestosoft.com/ps.asp?page=edp_examdiff
* Compare It! http://www.grigsoft.com/wincmp3.htm
* Diffuse https://sourceforge.net/projects/diffuse
* N++ https://sourceforge.net/projects/npp-compare
* Araxis merge http://www.araxis.com/merge/
* DiffMerge http://www.sourcegear.com/diffmerge/    
* Perforce Visual Merge https://www.perforce.com/product/components/perforce-visual-merge-and-diff-tools
* SemanticMerge https://www.semanticmerge.com/index.html
* DiffPlug https://www.diffplug.com/
* [xxdiff](http://furius.ca/xxdiff/)
* [Meld](http://meldmerge.org/)

## Image and CAD file diff

* Perceptual Image Diff https://sourceforge.net/projects/pdiff/
* Beyond Compare http://www.scootersoftware.com/

* Fast File Diff (see AutoDesk Forum topic https://apps.autodesk.com/ACD/en/Detail/HelpDoc?appId=4961723067758954084&appLang=en&os=Win32_64#contactinfo)
* CAD Diff http://soft.postpdm.com/cad_diff.html

## Special Diff

* [nbdime](https://github.com/jupyter/nbdime) - diffing and merging of Jupyter notebooks

# Code hosting

* https://github.com/ripienaar/free-for-dev#source-code-repos

## Self-hosting

### Git

* [Gitea](https://github.com/go-gitea/gitea)
* [GitLab](https://about.gitlab.com/)
  * [How to Setup GitLab: A Self Hosted GitHub](https://scotch.io/tutorials/how-to-setup-gitlab-a-self-hosted-github)
* [Gogs.io](https://gogs.io/) - cross-platform  self-hosted Git service
### SVN

* [Visual SVN Server](https://www.visualsvn.com/server/)

# Merging and sharing
* [Copybara](https://github.com/google/copybara) Tool for transforming and moving code between repositories.
* [meta](https://github.com/mateodelnorte/meta)  Tool for turning many repos into a meta repo.
* [mfetch_upstream](https://github.com/andylamp/mfetch_upstreams)  Fetches upstream and merges from multiple repositories.
* [fbshipit](https://github.com/facebook/fbshipit)  Tool to copy commits between repositories.
* [git-bzr-ng](https://github.com/termie/git-bzr-ng)  Bi-directional git to bzr bridge.
* [git-tf](https://github.com/nodirt/git-tf) Simple two-way Git-TFS bridge.
* [gitbitlabhub](https://github.com/karser/gitbitlabhub)  Tool to mirror repositories between Bitbucket, Gitlab, and Github.
* [github-action-build-chain](https://github.com/kiegroup/github-action-build-chain)  Tool for github actions to build multiple projects from different repositories.
* [github-repository-sync-action](https://github.com/net-engine/github-repository-sync-action)  Github action to push changes to branch in github repository to any remote repository.
* [github-sync](https://github.com/repo-sync/github-sync)  Github Actionfor syncing current repository with remote.
* [gitman](https://github.com/seanpm2001/gitman)  Tool for Git to help manage, fetch upstream, and modify projects through various Git websites.
* [git-merge-repos](https://github.com/robinst/git-merge-repos)  Program for merging multiple Git repositories into one.
* [peru](https://github.com/buildinspace/peru)  Tool for including other people's code in your project.
* [repository-mirroring-action](https://github.com/pixta-dev/repository-mirroring-action)  Github Action for mirroring a repository to another repository.
* [sparkleshare](https://github.com/hbons/SparkleShare)  Tool for sharing and collaborating through synchronized Git repos.
* [svnAndGit](https://github.com/innerhippy/svnAndGit)  Script to allow two-way workflow between git and subversion.

# Contributing

Just fork and send a pull request with your awesome Version control tools - clients, diffs etc.

