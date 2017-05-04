
This is a synthesio ansible role
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Intro
=====

The kernel role deploys and configures debian kernels

debian-kernel role parameters
-----------------------------

here is the current defaults as example

```
kernel_config:
    debian:
        stretch:
            -
                name: 'linux-image-amd64'
                state: 'latest'
        jessie:
            -
                name: 'linux-image-4.9.0-0.bpo.2-amd64'
                default_release: 'jessie-backports'
            -
                name: 'linux-base=4.3~bpo8+1'
                default_release: 'jessie-backports'

```
