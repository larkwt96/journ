# journ

A journaling program for your innovative ideas, random thoughts, and memorable events.

## How to use
```
journ {command} [args..]
Commands:
  n, or new   - New Journal
  r, or read  - Read from Journal
  w, or write - Write in Journal
  l, or list  - List Journals
  d, or del   - Delete Journal
``` 

### Create a new journal
```
journ n[ew] name
```
Creates a new journal with specified name.

### Read from a journal
```
journ r[ead] name
```
Displays specified journal with less.

### Write to a journal
```
journ w[rite] name
```
Writes to specified journal. Get's content from EDITOR, or vim if not specified.

### List journals
```
journ l[ist]
```
Lists existing journals.

### Delete a journal
```
journ d[el] name
```
Deletes specified journal (without confirmation).

## Environment Variables

```
VIEWER - Used to view journals (default: less).
EDITOR - Used to edit journal entries (default: vim).
```
