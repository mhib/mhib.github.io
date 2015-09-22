---
layout: post
title: "Multi-process Merge Sort in Elixir"
date: 2015-09-22T13:40:47+02:00
---

[Rosetta Code](http://rosettacode.org) has a multi-process merge sort implementation in Erlang, but not in Elixir, so I wrote it.

<script src="https://gist.github.com/mhib/e848295263f47f5701d6.js"></script>
It is using Erlang's standard library merge fuction.
Merge function implementation in Elixir:
<script src="https://gist.github.com/mhib/8b97dd60b0035a650dd1.js"></script>

