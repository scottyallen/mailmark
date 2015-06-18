Mailmark
========

Mailmark is a markov chain generator that uses mailing list archives to generate synthetic emails as though
they were written by a mailing list member of your choice.

Requirements
------------

* Virtualenv

Installation
------------

Clone this repo, and then run:

  virtualenv virtualenv
  source virtualenv/bin/activate
  pip install -r requirements.txt

Usage:

  python mailmark.py <mailing list archive url> <email address>
