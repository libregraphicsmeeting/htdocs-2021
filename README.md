# Website for the Libre Graphics Meeting 2021

Notes to the webmain:

- Please do not put original assets (that are not directly used for the website) in `public/`.  
  Create an `assets/` directory or ask for a `htdocs-2021-assets` repository.
- Please do not put the `vendor` directory in this repository.  
  We can run `composer install` on the server whenever it's neeeded.
- Put the stuff that should be reached by http in the `public` directory.  
  Keep all Php code that should not be directly reached in `private/`.  
  If you have Php scripts in `public/`, they can be load the libraries from `../../php-include/2021/`.
