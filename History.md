
0.4.0 / 2016-10-06
==================

  * Raise RuntimeError instead of returning `nil`

0.3.0 / 2016-01-23
==================

  * Prefer prefix ++/-- operators for non-primitive types
  * Add Debian::AptPkg::PkgCache.update

0.2.0 / 2016-01-04
==================

  * Fix cache count methods when not init
  * Add init, init_{config,system}
  * Add PkgCache.is_multi_arch method

0.1.0 / 2015-12-20
==================

  * Change VERSION, APT_VERSION and LIBAPT_PKG_VERSION
  * Add cache count methods
  * Fix rake lint task exit status
  * Fix syntax offences

0.0.4 / 2015-12-19
==================

  * Simple search with `Debian::AptPkg::PkgCache.pkg_names("vim")`
  * Documentation update
