gocache
=======
[![Build Status](https://travis-ci.org/ghais/gocache.png?branch=master)](https://travis-ci.org/ghais/gocache)

A General LRU Caching for Go


This is a fork from the [LRU Cache][1] implementation by [vitess][2] to support keys of any type for which equality is defined.

The performance is lower than that of Vitess Cache which supports string keys only (see here https://codereview.appspot.com/6501079/).


[1]: http://code.google.com/p/vitess/source/browse/go/cache/lru_cache.go "LRU Cache"
[2]: http://code.google.com/p/vitess/ "Vitess"
