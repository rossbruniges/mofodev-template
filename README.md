# Mozilla Foundation - Base template

A template that can be used as a start point for a new Mozilla Foundation project and hopefully ensure that we're all developing on a consistent base.

## IMPORTANT NOTE

With the iminent arrival of the one mozilla project http://onemozilla.org/ this will change signficantly. But if you've got a desparate need for a site now then please use.

## Responsive design

The template comes with a breakpoint at around 320px to support iPhone and android handheld mobile devices (smart phones).

All your base styles should live in devices.css (this will get applied everywhere) with your desktop specific stuff going into desktop.css - which will kick in when a user is using a viewport of around 320px and over. Further breakpoints can be added in desktop.css as required by your project.

### Browser support

The template has been tested to work in all modern browsers. Meaning IE8+ and the latest versions of FF, Safari, Opera, Chrome, Mobile Safair and in my Galaxy Tab.

IE8 doesn't support media queries so get's the full desktop view regardless of it's viewport width. This seemed a fair compromoise.

## Content

I think other than the 'connect with Mozilla' section the content can be changed to be specific to your project.

I would also recommend putting your branding inside of the <header> in #masthead, along with anything else you see fit.

### ID and class attributes for <div role='main'>

I've found these to be a great help in the past when a site grows out of the original scope of what it was intended (which to be honest is always). 

The ID is a unique identifier for the single page. If you ever need JS and CSS to only appear on that page you can prefix it using that ID.

The class is great for when you want to theme a specific section different to the rest of the site.

#### Example usage

Say you had a page at /about/rules.html. I would code it up as so:

<div role="main" id="rules" class="about">
