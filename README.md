# Git-intro
## History of Git
Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git.

### Download Git
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.

> Git can be installed in three ways:

1- Install as a package

2- Install via another installer

3- Download and compile the source code.


### So, what is Git?

**napshots**

- Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

**Local Operations**

- Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

**Tracking Changes**

- Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

**Loss of Data**

- Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

**States**

- Files in Git can reside in three main states: committed, modified and staged.

**Committed**

- Data is securely stored in a local database

**Modified**

- File has been changed but not committed to the database


:relaxed:
