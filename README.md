# Go sigar

## Overview

Go sigar is a golang implementation of the
[sigar API](https://github.com/hyperic/sigar).  The Go version of
sigar has a very similar interface, but is being written from scratch
in pure go/cgo, rather than cgo bindings for libsigar.

## Test drive

    $ go get github.com/cloudfoundry/gosigar
    $ cd $GOPATH/src/github.com/cloudfoundry/gosigar/examples
    $ go run uptime.go

## Using gerrit

    $ export GOPATH=~/gocode
    $ mkdir -p $GOPATH/src/github.com/cloudfoundry
    $ cd $GOPATH/src/github.com/cloudfoundry
    $ gerrit clone ssh://[<your username>@]reviews.cloudfoundry.org:29418/gosigar.git
    $ cd gosigar
    $ go test

## Supported platforms

Currently targeting modern flavors of darwin and linux.

## License

Apache 2.0

## File a Bug

To file a bug against Cloud Foundry Open Source and its components, sign up and use our
bug tracking system: [http://cloudfoundry.atlassian.net](http://cloudfoundry.atlassian.net)

