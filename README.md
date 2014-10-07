Stata-modules
=============

A collection of small Stata utilities. Minimal documentation for now. 

Install
=======

To install to install 'package' whose name begins with letter 'p' you can do the following with Stata v13.

```
. net install <package>, from(https://raw.githubusercontent.com/bquistorff/Stata-modules/master/<p>/) replace
```

For Stata 12 or below (that can't handle the https of github) download as zip, unzip, and then 

```
. net install <package>, from(full_local_path_to_files/<p>/) replace
```

Why not SSC?
=======

While I'm not opposed to having code on BC's SSC for convenience, that archive has several limitations:
* It doesn't allow access to previous versions of files (which is essential for replication). 
* It doesn't facilitate noting bugs or other comments (which reduces errors)
* It doesn't facilitate collaborative editing such as submitting bug fixes or tracking forks (which speeds development).


Author
=======
Brian Quistorff - quistorff (at) econ.umd.edu
I welcome comments (or pull-requests).
