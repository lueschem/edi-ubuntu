# edi-ubuntu

edi is mainly being developed using Ubuntu 16.04 LTS.
To do some random testing on the newer Ubuntu releases I use this edi configuration to setup an Ubuntu container.

Example:

``` bash
sudo edi -v lxc configure ubuntu-artful artful.yml
```

Within the container edi can be setup according to the [getting started guide](http://docs.get-edi.io/en/latest/getting_started.html).

The following tests verify the basic functionality:

``` bash
py.test-3
sudo py.test-3 --all
```
