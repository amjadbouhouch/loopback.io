---
lang: en
title: 'API docs: express.createinterceptor'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/express
permalink: /doc/en/lb4/apidocs.express.createinterceptor.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/express](./express.md) &gt; [createInterceptor](./express.createinterceptor.md)

## createInterceptor() function

Create an interceptor function from express middleware.

<b>Signature:</b>

```typescript
export declare function createInterceptor<CFG, CTX extends Context = InvocationContext>(middlewareFactory: ExpressMiddlewareFactory<CFG>, middlewareConfig?: CFG): GenericInterceptor<CTX>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  middlewareFactory | [ExpressMiddlewareFactory](./express.expressmiddlewarefactory.md)<!-- -->&lt;CFG&gt; | Express middleware factory function. A wrapper can be created if the Express middleware module does not conform to the factory pattern and signature. |
|  middlewareConfig | CFG | Configuration for the Express middleware |

<b>Returns:</b>

[GenericInterceptor](./context.genericinterceptor.md)<!-- -->&lt;CTX&gt;

