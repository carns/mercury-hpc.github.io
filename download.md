---
layout: page
title: Download
permalink: /download/
---

Mercury is distributed under a [BSD-like license][license].

## Releases

Filename                           | Date       | Size    | Arch | Type
---------------------------------- | ---------- | ------- | ---- | -----------
[mercury-0.9.0.tar.bz2][0.9.0]     | 2017-01-25 | 392 kB  | Any  | Source .bz2

Older releases are available [here][ftp]. Releases can also be accessed
through [GitHub][gh-releases], beware that generated tarballs do not
include mchecksum/kwsys submodules.

[license]: https://github.com/mercury-hpc/mercury/blob/master/COPYING
[0.9.0]: ftp://ftp.mcs.anl.gov/pub/mercury/releases/mercury-0.9.0.tar.bz2
[ftp]: ftp://ftp.mcs.anl.gov/pub/mercury/releases/
[gh-releases]: https://github.com/mercury-hpc/mercury/releases

## Current development distribution

The mercury repository is hosted on GitHub at:
[https://github.com/mercury-hpc/mercury](https://github.com/mercury-hpc/mercury)

To get the source (read-only access), simply run:
{% highlight bash %}
git clone --recurse-submodules https://github.com/mercury-hpc/mercury.git 
{% endhighlight %}
