Overview
--------

Reloader is the fantastic reloader.erl from mochiweb packaged into an
application. Use reloader during development to automatically reload 
modules when they are compiled. It also re-runs tests if the 
test/0 method is exported

Getting Started
---------------

If you're using rebar (try it, it's great), you can add this to you
rebar.config: ::

  {deps, [
    {reloader, "0.1", {git,
    "http://github.com/bjnortier/reloader.git", "master"}}
  }

then: ::

  application:start(reloader)

Otherwise you can built it with: ::

  $./rebar compile

and add to you load path with using your preferred method.

