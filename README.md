NFS Storage Backend for Cinder
-------------------------------

Overview
========

This charm provides a NFS storage backend for use with the Cinder
charm.

To use:

    juju deploy cinder
    juju deploy cinder-nfs
    juju add-relation cinder-nfs cinder

Configuration
=============

See config.yaml for details of configuration options.
