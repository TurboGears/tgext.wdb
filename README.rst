tgext.wdb
======================

WDB - Web Debugger support for TurboGears, replaces the backlash
debugger with WDB.

Usage
------------

Inside your ``config/app_cfg.py`` enable the WDB debugger::

    from tgext.wdb import enable_wdb
    
    enable_wdb(base_config)

Make sure you started the WDB server before using it::

    $ wdb.server.py


