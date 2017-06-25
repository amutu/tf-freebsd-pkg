# tf-freebsd-pkg

NOTE: This is NOT the offical FreeBSD tensorflow pkg, use at your own risk.  

For tensorflow-1.2.0,there is a new runtime dependency named backports.weakref which do not port to FreeBSD. I port it on [PR 220206](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=220206). Before it committed, you can install from the same dir,the package name is py(27|36)-backports.weakref-1.0.r1.txz. Please install it first,then install the tensorflow package.
