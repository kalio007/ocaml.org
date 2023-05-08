---
title: Ocamlformat 0.8
date: "2018-10-10"
tags: [ocamlformat, platform, release]
changelog: |
  - Improve: set break-sequences in sparse and compact profiles (#455, @jberdine)
  - Improve: keep a space inside tuples parens (#453, @gpetiot)
  - Improve: --root option to isolate configuration files (#402, @gpetiot)
  - Fix: missing parens around partially-applied `::` (#452, @jberdine)
  - Fix: parens around expressions with attributes (#441, @gpetiot)
  - Build: do not execute shell scripts directly in build (#448, @dra27)
  - Add: read ocp indent config files (#445, @gpetiot)
  - Improve: option 'break-sequences' (#434, @gpetiot)
  - Improve: option 'no-indicate-multiline-delimiters' to have less whitespaces (#429, @gpetiot)
  - Fix: outdent before arrow (#444, @gpetiot)
  - Improve: User documentation (#449, @gpetiot)
  - Improve: option 'cases-exp-indent' to adjust indent (#428, @gpetiot)
  - Add: compact and sparse profiles (#408, @jberdine)
  - Improve: explicit error message in case of 'permission denied' error (#425, @gpetiot)
  - Fix: comment stabilization in Pexp_override (#422, @gpetiot)
  - Fix: corner case while formatting type variables (#440, @hhugo)
  - Fix: many missing comments (#418, @hhugo)
  - Fix: asserts and attributes (#414, @hhugo)
  - Fix: extension and attribute (#417, @hhugo)
  - Improve: support for `function%ext` (#416, @hhugo)
  - Fix: Inconsistent spacing around comments in signatures vs structures (#437, @gpetiot)
  - Improve: better error with location when comment dropped (#401, @gpetiot)
  - Fix doc comments (#413, @hhugo)
  - Improve: use input_name for error messages (@hhugo)
  - Improve: break after inherit (@hhugo)
  - Fix: aliases inside constructor declaration (#424, @gpetiot)
  - Fix: broken invariant for Pmod_unpack (#421, @gpetiot)
  - Fix: print error details in debug mode only (#420, @hhugo)
  - Fix: mark_parenzed_inner_nested_match (@hhugo)
  - Improve: tune the janestreet profile (@hhugo)
  - Improve: disable ocamlformat if no dot ocamlformat in the project (#391, @hhugo)
  - Improve: new option to control spacing around let bindings (#344, @hhugo)
  - Fix: prec of string/array sugar (#381, @hhugo)
  - Fix: lost comment in constraint expression (#400, @gpetiot)
  - Fix: lost cmt near functor (#399, @gpetiot)
  - Improve: preset profiles (default & janestreet) (#390, @gpetiot)
  - Improve: try to fit simple list/array elements on a single line (#375, @gpetiot)
  - Fix: bad comment spacing with module-item-spacing=compact (#395, @gpetiot)
  - Fix: dropped comment in revapply of extension (#394, @gpetiot)
  - Improve: let-and structures spacing depends on module-item-spacing (#367, @gpetiot)
  - Fix: consecutive prefix operator (#386, @hhugo)
  - Fix: invalid (#383, @hhugo)
  - Fix: lazy and alias (#388, @hhugo)
  - Improve: main loop and error reporting (#389, @hhugo)
  - Fix: exposed_left_typ (#385, @hhugo)
  - Fix: rec functor (#382, @hhugo)
  - Fix: `while%ext`/`for%ext` (@hhugo)
  - Fix: more on class (@hhugo)
  - Fix: invalid syntax on class (@hhugo)
  - Improve: follow XDG for global config files (@gpetiot)
  - Improve: add support for bigarray sugar index operator (@hhugo)
  - Add: support reading input from stdin (#353, @bkase)
  - Fix: the precedence of options (@gpetiot)
  - Improve: doc of config option choice alternatives (#354, @jberdine)
  - Improve: string formatting (@hhugo)
---
