# vhostman for Linux

What is it?
===========

A little PHP script to quickly add, remove or list vhosts to your local apache configuration for development purposes on Linux.

Installation
============
    
Ensure it's executable:

    chmod u+x /path/to/vhostman
    
Link this into your /usr/local/bin like so:

    ln -s /path/to/vhostman /usr/local/bin/vhostman

Usage
=====

Show existing vhosts

    sudo vhostman list

Add a new vhost

    sudo vhostman add example.local ~/path/to/example

Remove an existing vhost

    sudo vhostman rm example.local