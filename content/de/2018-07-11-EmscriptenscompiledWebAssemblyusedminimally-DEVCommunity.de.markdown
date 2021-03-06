---
slug: EmscriptenscompiledWebAssemblyusedminimally-DEVCommunity
date: 2018-07-11T21:05:59.091Z
title: Emscripten's compiled Web Assembly, used minimally
link: https://dev.to/samthor/emscriptens-compiled-web-assembly-used-minimally-4fd4
tags: ['link', 'wasm']
---
Sam Thorogood auf Dev.to schreibt,

> Why did I write this post? Emscripten is a wonderful tool, but it has a long history (for asm.js), and isn't perfect. I think it errs too much on the side of "magic", and many posts rave about how it's so easy to EM_ASM_ or use binding-fu, but this all comes at a cost, and can introduce huge amounts of inadvertent overhead&#x2014;think copying huge memory buffers around because we're trying to make them immutable or easily exposed.
> 
> Every language that is being compiled to Web Assembly needs a runtime&#x2014;whether it be Go, or Rust, or C/C++ as we have here. I don't believe that we'll ever really be able to directly import Web Assembly via ES2015 modules, at least not without changes on the JS side. But it behooves us to write the smallest one we possibly can.


[Ganzen Beitrag lesen](https://dev.to/samthor/emscriptens-compiled-web-assembly-used-minimally-4fd4).

Ich denke, wir alle sehen das Potenzial von Wasm, etwas für viele von uns, viele der anderen Plattformen, die jetzt ins Web kommen können, sind uns völlig fremd, und wir müssen diese Tools wirklich lernen, um die Erfahrung der Entwickler von Wasm zu verbessern und imo bieten vorgefertigte Bibliotheken, die "traditionelle Webentwickler" einfach verwenden können.
