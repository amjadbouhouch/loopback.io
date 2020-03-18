---
lang: en
title: 'API docs: repository.defaultcrudrepository.definepersistedmodel'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.defaultcrudrepository.definepersistedmodel.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [DefaultCrudRepository](./repository.defaultcrudrepository.md) &gt; [definePersistedModel](./repository.defaultcrudrepository.definepersistedmodel.md)

## DefaultCrudRepository.definePersistedModel() method

Creates a legacy persisted model class, attaches it to the datasource and returns it. This method can be overriden in sub-classes to acess methods and properties in the generated model class.

<b>Signature:</b>

```typescript
protected definePersistedModel(entityClass: typeof Model): typeof juggler.PersistedModel;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  entityClass | <code>typeof Model</code> | LB4 Entity constructor |

<b>Returns:</b>

`typeof juggler.PersistedModel`

