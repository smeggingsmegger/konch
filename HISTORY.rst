*********
Changelog
*********

0.3.1 (2014-03-17)
------------------

- Doesn't change current working directory.
- Less magicks.
- Tested on Python 3.4.


0.3.0 (2014-03-16)
------------------

- Smarter path resolution. konch will search parent directories until it finds a .konchrc file to use.
- Make prompt configurable on IPython and built-in shell. Output template is also supported on IPython.
- *Backwards-incompatible*: Remove support for old (<=0.10.x--released 3 years ago!) versions of IPython.

0.2.0 (2014-03-15)
------------------

- Fix bug with importing modules and packages in the current working directory.
- Introducing *named configs*.

0.1.0 (2014-03-14)
------------------

- First release to PyPI.
