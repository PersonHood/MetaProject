[  this is a comment. ]::

<link href="styles.css" rel="stylesheet"></link>

> [MetaProject](../MetaProject.md) | [Appendices](./MetaProject-00-Appendices.md) | [WTF](./MetaProject-01-WTF.md) | [Motivate](./MetaProject-02-Motivate.md) 
> [Overview](./MetaProject-03-Overview.md) | [Definitions](./MetaProject-04-Definitions.md) | [Memes](./MetaProject-05-Memes.md) | [Admin](./MetaProject-06-Admin.md) 
> [TT4N](./MetaProject-07-TT4N.md) | [Hosts](./MetaProject-08-Hosts.md) | [Bibliography](./MetaProject-99-Bibliography.md) 

# Admin

- MetaProject-06-Admin.md

Several `bash` scripts are employed
> `./MetaProject/bash/2b*

A directory structure and files are employed
> `./TEMPLATE/TEMPLATE.md` *et al*

Each `script` addresses a specific need:

- 2bmake PROJDIR ProjectName
  - create the new directory structure
    - `./PROJDIR/` *et al*
  - copy files
  - rename files
    - `TEMPLATE*` -> `ProjectName*`
  - change TEMPLATE contents
    - `TEMPLATE` -> `ProjectName`
- Manage data and files
  - 2bmd2tab
  - 2bmd2csv
  - 2bmd2html
  - 2bmerge
  - 2bsplit
  - 2btouch
  - 2bgone
- Manage Sites
  - 2bhost - upload to GitHub *et al*
  - 2bmove - rename
  - 2bdupe - sub-template
  - 2barch - remove, zip archive
- Manage Server
  - YAML - `Jekyll`
  - CSS
