my-vault
========

Automated backup of directories to a vault 'à la Time Machine' with less features and less restrictions for Linux.

Features:
- uses rsync;
- snapshot allows quick restoring a directory or file from the vault to its original location;
- previous versions of a file are kept;
- automatic purging of expired old versions (days of freshness is configurable);
- it lacks a nice GUI for selecting previous versions of file, yet.
