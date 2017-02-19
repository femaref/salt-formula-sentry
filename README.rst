
==============
Sentry formula
==============

Sentry is a realtime event logging and aggregation platform. At its core it
specializes in monitoring errors and extracting all the information needed to
do a proper post-mortem without any of the hassle of the standard user
feedback loop.

It’s important to note that Sentry should not be thought of as a log stream,
but as an event aggregator. It fits somewhere in-between a simple metrics
solution (such as Graphite) and a full-on log stream aggregator (like
Logstash).


Sample pillars
==============

Standalone server

.. literalinclude:: tests/pillar/standalone_server.sls
   :language: yaml

Server behind proxy

.. literalinclude:: tests/pillar/proxy_server.sls
   :language: yaml


More information
================

* https://github.com/getsentry/sentry
* https://docs.sentry.io/server/installation/


Documentation and Bugs
======================

To learn how to install and update salt-formulas, consult the documentation
available online at:

    http://salt-formulas.readthedocs.io/

In the unfortunate event that bugs are discovered, they should be reported to
the appropriate issue tracker. Use Github issue tracker for specific salt
formula:

    https://github.com/salt-formulas/salt-formula-sentry/issues

For feature requests, bug reports or blueprints affecting entire ecosystem,
use Launchpad salt-formulas project:

    https://launchpad.net/salt-formulas

You can also join salt-formulas-users team and subscribe to mailing list:

    https://launchpad.net/~salt-formulas-users

Developers wishing to work on the salt-formulas projects should always base
their work on master branch and submit pull request against specific formula.

    https://github.com/salt-formulas/salt-formula-sentry

Any questions or feedback is always welcome so feel free to join our IRC
channel:

    #salt-formulas @ irc.freenode.net
