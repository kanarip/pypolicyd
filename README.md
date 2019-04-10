## Simple Python Postfix SMTP Access Policy daemon for distributed environments

This is a simple implementation of a Postfix SMTP Access Policy daemon in Python, for use
in distributed environments.

At the moment, it implements a rate limitation for senders, to be applied on external outbound mail
exchangers, along with an opportunity to whitelist entire domains or individual email addresses.
