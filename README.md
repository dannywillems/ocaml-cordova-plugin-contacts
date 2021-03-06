# ocaml-cordova-plugin-contacts

[![LGPL-v3 licensed](https://img.shields.io/badge/license-LGPLv3-blue.svg)](https://raw.githubusercontent.com/dannywillems/ocaml-cordova-plugin-contacts/master/LICENSE)
[![Build Status](https://travis-ci.org/dannywillems/ocaml-cordova-plugin-contacts.svg?branch=master)](https://travis-ci.org/dannywillems/ocaml-cordova-plugin-contacts)

Binding to
[cordova-plugin-contacts](https://github.com/apache/cordova-plugin-contacts)

## What does cordova-plugin-contacts do ?

```
This plugin defines a global `navigator.contacts` object, which provides access
to the device contacts database.
```

Source: [cordova-plugin-contacts](https://github.com/apache/cordova-plugin-contacts)

## Repository branches and tags

We are migrating bindings from
[js_of_ocaml](https://github.com/ocsigen/js_of_ocaml) (low level bindings) to
[gen_js_api](https://github.com/lexifi/gen_js_api) (high level bindings).

The gen_js_api binding allows to use *pure* ocaml types (you don't have to use
the ## syntax from js_of_ocaml or Js.string type but only # and string type).

The js_of_ocaml version is available in the branch
[*js_of_ocaml*](https://github.com/dannywillems/ocaml-cordova-plugin-contacts/tree/js_of_ocaml)
but we **recommend** to use the gen_js_api version which is the master branch.

## How to use ?

TODO
