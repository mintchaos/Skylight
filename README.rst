Skylight is a Textual irc style. http://www.codeux.com/textual/

It makes me happy.

To install dump this folder into ~/Library/Application Support/Textual/Styles

It looks like this: 

.. image:: http://img.skitch.com/20101029-n44seaf65ph3nd861dbear9e5y.png


Important notes and warnings:
============================

You need be using the default time stamps in this format:
[%m/%d/%Y -:- %I:%M:%S %p]

At this point Textual uses the the timestamp as set in the preferences for the
logs. This theme is opinionated about time stamps and edits them via JS but
expects them to start in this format.

Also note that Skylight screws with the DOM and switching to skylight or from
Skylight and other styles may require a restart or some other form or
resetting the current channels.



Tricks
======

* Usernames and messages are aligned.
* Multiple messages from the same user only display the username for the first 
  message.
* Time stamps are simplified down and only shown when the time changes.
* Dates are shown in a nice conversation marking badge, but again only when 
  they change.
* Clicking on a username will highlight all messages from that user in the 
  active channel. Clicking again will clear, clicking on someone else with 
  switch.



Props
=====

This style contains some code from the Simplified style that ships with Textual & contains some ideas from the Simplified theme for Linkinus by "Cowboy" Ben Alman (http://benalman.com/). 

Scripts.js contains a copy of jQuery by John Resig
