Roadmap
=======

This document should give a quick overview of what is to be done.

Directory Structure
-------------------

The directory structure should include a branch name, to allow
multi-user-multi-branch development. Target files should be available
at ``<target_dir>/<repo_name>/<branch_name>/`` or so.

As of commit 2bca859 this is the case!

Configuration File
------------------

The compilation should use a makefile, but the target should be
selectable by the user. Furthermore, the user should be able to configure
primary targets (pdf files, etc.) and secondary targets (logfiles).

User Interface
--------------

The system should include a user interface with information regarding
compile status, logfile display and possibly a small and simple
configuration interface.
At some point the ``stdout`` of the build process should be available
as a web stream with syntax highlighting and build error analyzation
(tabular display for those who don't like poring about logfiles).
The generation of travis-like ``build: passing`` status images would be nice as well.

Bitbucket integration
---------------------

The server should work with Bitbucket as well.
Possibility to include read-access-only `Deployment Keys <https://confluence.atlassian.com/x/I4CNEQ>`_
would be nice.

Add Logging support
-------------------

Include the python Logging module to be able to split the server logs from compile logs.
