Mono Cloudfoundry Buildpack
=====================

It serves files using [XSP](http://www.mono-project.com/ASP.NET#ASP.NET_hosting_with_XSP).

Usage
-----

Example usage:

    $ cf push my-app-name --builldpack http://github.com/cdan/cf-mono-buildpack.git

The buildpack will detect your app as Mono if it has the file `global.asax` in the root or at one directory depth.



