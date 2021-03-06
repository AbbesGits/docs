---
layout: default
language: 'tr-tr'
version: '4.0'
title: 'Phalcon\Mvc\Model\MetaData\Strategy\Introspection'
---
# Class **Phalcon\Mvc\Model\MetaData\Strategy\Introspection**

*implements* [Phalcon\Mvc\Model\MetaData\StrategyInterface](Phalcon_Mvc_Model_MetaData_StrategyInterface)

[Source on GitHub](https://github.com/phalcon/cphalcon/tree/v{{ page.version }}.0/phalcon/mvc/model/metadata/strategy/introspection.zep)

Queries the table meta-data in order to introspect the model's metadata

## Methods

final public **getMetaData** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, [Phalcon\DiInterface](Phalcon_DiInterface) $dependencyInjector)

The meta-data is obtained by reading the column descriptions from the database information schema

final public **getColumnMaps** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, [Phalcon\DiInterface](Phalcon_DiInterface) $dependencyInjector)

Çıkarılamayacak olan modelin sütun haritasını okuyun.