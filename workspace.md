## Workspace management

Philosopher works with the concept of workspaces, all processed and parsed data is stored localy in a custom binary format providing a more efficient way of handlign data.

### Usage

`philosopher workspace [flags]`

## Flags

`--init`

Initialize the workspace. Should be executed on the place where the other files are.

`--backup`

Create a backup of the experiment meta data in .zip format.

`--clean`

Remove the workspace and all meta data. Experimental file are kept intact.
