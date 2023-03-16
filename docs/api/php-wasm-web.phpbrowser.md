<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## PHPBrowser class

<b>Signature:</b>

```typescript
class PHPBrowser implements WithRequest
```

<b>Implements:</b> [WithRequest](./php-wasm-web.withrequest.md)

A fake web browser that handles PHPServer's cookies and redirects
internally without exposing them to the consumer.

## Constructors

### PHPBrowser<!-- -->(<!-- -->server<!-- -->: [PHPServer](./php-wasm-web.phpserver.md)<!-- -->, config?<!-- -->: [PHPBrowserConfiguration](./php-wasm-web.phpbrowserconfiguration.md)<!-- -->)

-   `server` – The PHP server to browse.
-   `config` – Optional. The browser configuration.

Constructs a new instance of the `PHPBrowser` class

## Properties

-   `server` [PHPServer](./php-wasm-web.phpserver.md)

## Methods

### request<!-- -->(<!-- -->request<!-- -->: [PHPServerRequest](./php-wasm-web.phpserverrequest.md)<!-- -->, redirects?<!-- -->: [number](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[PHPResponse](./php-wasm-web.phpresponse.md)<!-- -->&gt;

-   `redirects` – Optional.