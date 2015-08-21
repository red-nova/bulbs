## What is Bulbs?
An open source forum engine created by Galileo94 in Python using the pyramid web framework.

## Is it ready for production yet?
Nope, the current release version is: **0.1dev**, still have a shit ton of stuff to iron out.

## Is it secure?
I dunno, maybe. Probably not.

## Requirements
* Python 3.4+
* Pyramid
* PostgreSQL database with the _pgcrypto_ extension

## How to install
* Clone the github repository, `git clone https://github.com/Galileo94/bulbs.git`
* Switch into your virtualenv if you're using it
* `python setup.py develop` to install the package and dependencies
* `python setup.py configure` will prompt you for your database information
* If nothing exploded, you should be ready to rock and roll

