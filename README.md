# Distributed Components OPAM respository

All Distributed Components OPAM packages live here.

## Repository

To activate the repository:
    ```
    opam repo add distributed-components-packages http://opam.distributedcomponents.net
    ```

## OPAM metadata

We use the `tags` field of the `opam` file as follows:

 1. strings beginning with `keyword:` are considered as `keywords`
 2. strings beginning with `category:` are considered as `categories`
 3. a string beginning with `date:` is the date the software was last updated
    (not the package)

Example:

    tags: [ "keyword:cool" "keyword:stuff" "category:Some/Category" "date:1992-12-22" ]

Finally the `homepage:`, `author:`, `maintainer:` and `doc:` fields are
also used to generate the package entry.
