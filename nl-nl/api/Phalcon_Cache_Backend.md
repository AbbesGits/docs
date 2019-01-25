---
layout: article
language: 'nl-nl'
version: '4.0'
title: 'Phalcon\Cache\Backend'
---
# Abstract class **Phalcon\Cache\Backend**

*implements* [Phalcon\Cache\BackendInterface](Phalcon_Cache_BackendInterface)

[Source on GitHub](https://github.com/phalcon/cphalcon/tree/v{{ page.version }}.0/phalcon/cache/backend.zep)

This class implements common functionality for backend adapters. A backend cache adapter may extend this class

## Methods

public **getFrontend** ()

...

public **setFrontend** (*mixed* $frontend)

...

public **getOptions** ()

...

public **setOptions** (*mixed* $options)

...

public **getLastKey** ()

...

public **setLastKey** (*mixed* $lastKey)

...

public **__construct** ([Phalcon\Cache\FrontendInterface](Phalcon_Cache_FrontendInterface) $frontend, [*array* $options])

Phalcon\Cache\Backend constructor

public *mixed* **start** (*int* | *string* $keyName, [*int* $lifetime])

Starts a cache. The keyname allows to identify the created fragment

public **stop** ([*mixed* $stopBuffer])

Stops the frontend without store any cached content

public **isFresh** ()

Checks whether the last cache is fresh or cached

public **isStarted** ()

Checks whether the cache has starting buffering or not

public *int* **getLifetime** ()

Gets the last lifetime set

abstract public **get** (*mixed* $keyName, [*mixed* $lifetime]) inherited from [Phalcon\Cache\BackendInterface](Phalcon_Cache_BackendInterface)

...

abstract public **save** ([*mixed* $keyName], [*mixed* $content], [*mixed* $lifetime], [*mixed* $stopBuffer]) inherited from [Phalcon\Cache\BackendInterface](Phalcon_Cache_BackendInterface)

...

abstract public **delete** (*mixed* $keyName) inherited from [Phalcon\Cache\BackendInterface](Phalcon_Cache_BackendInterface)

...

abstract public **queryKeys** ([*mixed* $prefix]) inherited from [Phalcon\Cache\BackendInterface](Phalcon_Cache_BackendInterface)

...

abstract public **exists** ([*mixed* $keyName], [*mixed* $lifetime]) inherited from [Phalcon\Cache\BackendInterface](Phalcon_Cache_BackendInterface)

...