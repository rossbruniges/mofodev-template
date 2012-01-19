# Mozilla Foundation - Base template

A template that can be used as a start point for a new Mozilla Foundation project and hopefully ensure that we're all developing on a consistent base.

## IMPORTANT NOTE

With the iminent arrival of the one mozilla project http://onemozilla.org/ this will change signficantly. But if you've got a desparate need for a site now then please use.

## Responsive design

The template comes with a breakpoint at around 320px to support iPhone and android handheld mobile devices (smart phones).

All your base styles should live in devices.css (this will get applied everywhere) with your desktop specific stuff going into desktop.css - which will kick in when a user is using a viewport of around 320px and over. Further breakpoints can be added in desktop.css as required by your project.
