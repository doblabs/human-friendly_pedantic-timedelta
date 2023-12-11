############
Installation
############

.. vim:tw=0:ts=3:sw=3:et:norl:nospell:ft=rst

.. |virtualenv| replace:: ``virtualenv``
.. _virtualenv: https://virtualenv.pypa.io/en/latest/

.. |workon| replace:: ``workon``
.. _workon: https://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html?highlight=workon#workon

To install system-wide, run as superuser::

    $ pip3 install human-friendly_pedantic-timedelta

To install user-local, simply run::

    $ pip3 install -U human-friendly_pedantic-timedelta

To install within a |virtualenv|_, try::

    $ cd "$(mktemp -d)"

    $ python3 -m venv .venv

    $ . ./.venv/bin/activate

    (human-friendly_pedantic-timedelta) $ pip install human-friendly_pedantic-timedelta

To develop on the project, link to the source files instead::

    (human-friendly_pedantic-timedelta) $ deactivate
    $ git clone git@github.com:doblabs/human-friendly_pedantic-timedelta.git
    $ cd human-friendly_pedantic-timedelta
    $ python3 -m venv human-friendly_pedantic-timedelta
    $ . ./.venv/bin/activate
    (human-friendly_pedantic-timedelta) $ make develop

After creating the virtual environment, it's easy to start
developing from a fresh terminal::

    $ cd human-friendly_pedantic-timedelta
    $ . ./.venv/bin/activate
    (human-friendly_pedantic-timedelta) $ ...

