---
title: How is the code structured?
layout: post
categories: faqs
display-order: 4
---

## The project is broken into several independent toolkits:

* [oommfc](https://github.com/joommf/oommfc) : a low-level Python wrapper for
  running OOMMF simulations

* [oommffield](https://github.com/joommf-attic/oommffield): a Python module for reading, writing and plotting OMF files,
  outputted by OOMMF and other micromagnetics packages

* [oommfodt](https://github.com/joommf/oommfodt): a Python module which allows users to load ODT files into Pandas DataFrames
