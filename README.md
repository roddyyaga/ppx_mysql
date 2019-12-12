Ppx_mysql
=========

A fork of ppx\_mysql.

## Changes
- Bugfix that inserts Booleans properly

## Roadmap
- Short term:
  - Add a wrapper around ocaml-mysql's `Prepared.insert_id`

- Longer term:
  - Add support for floats
  - Wrap other ocaml-mysql functions
  - Check syntax of SQL at ppx time (so syntax errors can be caught by the type checker)
