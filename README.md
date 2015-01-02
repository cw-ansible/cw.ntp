<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.ntp.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.ntp)
[![Tweet this](http://img.shields.io/badge/%20-Tweet-00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2Fcw.ntp&text=Install%20and%20configure%20%23NTP%20using%20%23ansible.)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


# NTP

Install and configure NTP services.

## Usage

Include the `cw.ntp` module to your playbook.

## Description

This module will install `ntp` and `ntpdate` packages, make sure option `-u`
is set by default for `NTPOPTIONS` in `/etc/default/ntpdate`.

## Configuration

See specific documentation in `defaults/main.yml`

## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
