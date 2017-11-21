# ACM Latex Template 2017
- This is a modified version of ACM 2017 LaTex template.
- The project is tested on Overleaf.

## Changelist
- Use global numbering for theorems instead of sections.
- Enforce author first names in reference section to be initial.
- The maximum displayed author number can be adjusted by modifying ACM-Reference-Format.bst:1027

## TODO
- Original version will transform "and others" in the author field of .bib file
to "et al", but it's not supported in the current modification, because we
automatically cut the exceeded authors to "et al", although we should still
support "and others" so that we can compatible with all existing projects.

