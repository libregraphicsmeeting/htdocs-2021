# Website for the Libre Graphics Meeting 2021

Notes to the webmain:

- Please do not put original assets in the main branch of the repository.  
  Put them in a different branch or ask for a `htdocs-2021-assets` repository.
- Please do not put the `vendor` directory in this repository.  
  We can run `composer install` on the server whenever it is neeeded.
- If possible, put the stuff that should be reached by http in a `public` directory and keep all Php code that should not be directly reached out of it.

## Todo

- [x] Multpile basedir with a path each
