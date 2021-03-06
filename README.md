# psr-drift

Provides improved localization of pulsars using data from drift scans or RA/Dec.
mapping with single dish radio telescopes. The current implementation relies on folding raw
PSRFITS files with PRESTO (http://www.cv.nrao.edu/~sransom/presto/) and works with the 
resulting data products. More on how to acquire the code, a full list of dependencies,
and some tests with included files can be found below. A detailed description of the
localization technique and how it compares to others can be found in
Gentile & Swiggum (in prep.; *link*).

## Getting Started

To use psr-drift, you will need to make sure you have access to some other code, this
code, and you may want to run a few tests to make sure everything works.

### Dependencies

Before you can use psr-drift, make sure you have access to:

```
PRESTO
scipy
???
```

### Get psr-drift

To grab a copy of psr-drift, do:

```
git clone git://github.com/swiggumj/psr-drift.git
```

and to update it on a regular basis, `git pull` from your psr-drift directory.

### Testing & Usage

More soon...
