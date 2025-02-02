# Pyinotify

This is a fork of: [seb-m/pyinotify](https://github.com/seb-m/pyinotify).

I'm maintaining this fork, feel free to report any issues if something isn't working.

| License           | MIT                                                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Project URL       | [kacperpaczos/pyinotify: Monitoring filesystems events with inotify on Linux.](https://github.com/kacperpaczos/pyinotify) |
| Project Wiki      | [kacperpaczos/pyinotify Wiki](https://github.com/kacperpaczos/pyinotify/wiki)                                             |
| API Documentation | None                                                                                                                      |

## Dependencies

* Linux ≥ 2.6.13
* Python ≥ 2.4 (including Python 3.x)

## Installation

### Get the current stable version from PyPI and install it with `pip`

    # To install pip follow http://www.pip-installer.org/en/latest/installing.html
    $ sudo pip install pyinotify

### Or install Pyinotify directly from source

    # Choose your Python interpreter: either python, python2.7, python3.2,..
    # Replacing XXX accordingly, type:
    $ sudo pythonXXX setup.py install

## Watch a directory

Install pyinotify and run this command from a shell:

    $ python -m pyinotify -v /my-dir-to-watch
