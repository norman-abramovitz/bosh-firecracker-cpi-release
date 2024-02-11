# bosh-firecracker-cpi-release
create a BOSH cpi using [firecracker microVM](https://firecracker-microvm.github.io/) multi-tenant container services.

cpi program
1. json payloads are read from standard input
1. json payloads are written to standard out
1. json payloads are written to standard error for errors
1. exit

Using the following CPIs as models
* [alicloud-cpi](https://github.com/cloudfoundry-incubator/bosh-alicloud-cpi-release)
* [docker-cpi](https://github.com/cloudfoundry/bosh-docker-cpi-release/tree/master) 
* [google-cpi](https://github.com/cloudfoundry/bosh-google-cpi-release)

## BOSH

BOSH: [Build a CPI](https://bosh.io/docs/build-cpi/)

[BOSH cpi common functionality](https://github.com/cloudfoundry/bosh-utils)
* bosherr "github.com/cloudfoundry/bosh-utils/errors"
* boshlog "github.com/cloudfoundry/bosh-utils/logger"
* boshsys "github.com/cloudfoundry/bosh-utils/system"
* boshuuid "github.com/cloudfoundry/bosh-utils/uuid"

## Firecracker
[firecracker go sdk](https://github.com/firecracker-microvm/firecracker-go-sdk)


