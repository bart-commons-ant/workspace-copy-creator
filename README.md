# workspace-copy-creator

Overview
--------

Creates workspace copy. 

Parameters
----------

- workspace.src - Workspace to be copied.
- workspace.dest - Destination workspace (will be deleted if already exist).

Example usage
-------------

	ant -Dworkspace.src=example/foobar -Dworkspace.dest=example/foobar-copy