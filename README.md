# Lesson3_1

Это коммит из первого репозитория.

Он будет отображен в удалённом репозитории.

--progress
Progress status is reported on the standard error stream by default when it is attached to a terminal, unless -q is specified. This flag forces progress status even if the standard error stream is not directed to a terminal.

--all-progress
When --stdout is specified then progress report is displayed during the object count and compression phases but inhibited during the write-out phase. The reason is that in some cases the output stream is directly linked to another command which may wish to display progress status of its own as it processes incoming pack data. This flag is like --progress except that it forces progress report for the write-out phase as well even if --stdout is used.

--all-progress-implied
This is used to imply --all-progress whenever progress display is activated. Unlike --all-progress this flag doesn’t actually force any progress display by itself.

--version=<version>
Specify the bundle version. Version 2 is the older format and can only be used with SHA-1 repositories; the newer version 3 contains capabilities that permit extensions. The default is the oldest supported format, based on the hash algorithm in use.

-q
--quiet
This flag makes the command not to report its progress on the standard error stream.

