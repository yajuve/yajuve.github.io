---
layout: post
title:  "VSCode for Laravel"
categories: tuto
---

Here how i prepared my VSCode to code with **Laravel** PHP Framework

## Extensions

* PHP Intelephense
* Laravel (Official extension for Laravel)
* PHP Debug: To debug with xdebug

## Configuration

I found myself with a lot of autocompletion suggestion like super global varibale `$_COOKIE`, `$_ENV`, `$_FILE`
which are not useful, because i need the available porpoerteis or functions on my objects, facades.

To avoid this behaviour you have two approaches

* First (1) approach
  * Go to extensions tab (Ctrl+Shift+X)
  * Type @builtin php
  * disable `PHP Langauges Features` extension

* Second (2) approach
  * Update JSON settings (Ctrl+Shift+P) -> Open User Settings (JSON)
  * Add this line `"php.suggest.basic": false,` to disbale this feature
