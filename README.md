django-responsive-dashboard
===========================

[![Build Status](https://travis-ci.org/burke-software/django-responsive-dashboard.png?branch=master)](https://travis-ci.org/burke-software/django-responsive-dashboard)

A generic and easy dashboard for Django applications.

# News

Released 1.0. Not feature complete yet - but stable enough to run. Shouldn't need to make any more changes
that break things. Still need to add better documentation and tests.

![screenshot](/images/screen.png)

# Features
- jquery.shapeshift for positioning and ordering
- Per user saving of above
- Stock dashlets - Lists, RSS reader, Admin edit lists, django-report-builder, more to come.
- Add and remove dashlets (not implimented)
- Generic per user configurations on dashlets (not implimented)

## What it can't do
- No ready to use dashboard, you need need for it like contrib.admin.
- Column width is hard coded to 300px with 20px gutters. (Feel free to contribute)

django-responsive-dashboard is a starting point for your dashboard interface. It is not a drop in solution. 
A few dashlets are included, but you probably want to create your own. The included css is VERY minimal,
again you should create your own styling.

# Documentation

http://django-responsive-dashboard.readthedocs.org
