soft-morning-theme
==================

Emacs24 theme with a light background

![Screenshot](https://github.com/mswift42/soft-morning-theme/raw/master/Screenshot.png)

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("marmalade" . "http://marmalade-repo.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))

    (package-initialize)



This will add the gnu, marmalade and melpa repos to your emacs setup.

To install the theme

**M-x package-install** soft-morning-theme


To use the soft-morning theme when starting emacs, add this to your init.el:

    (load-theme 'soft-morning)




