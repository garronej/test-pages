[@foal/core](../README.md) > ["core/http/http-responses"](../modules/_core_http_http_responses_.md) > [HttpResponseMovedPermanently](../classes/_core_http_http_responses_.httpresponsemovedpermanently.md)

# Class: HttpResponseMovedPermanently

Represent an HTTP response with the status 301 - MOVED PERMANENTLY.

*__export__*: 

*__class__*: HttpResponseMovedPermanently

*__extends__*: {HttpResponseRedirection}

## Hierarchy

↳  [HttpResponseRedirection](_core_http_http_responses_.httpresponseredirection.md)

**↳ HttpResponseMovedPermanently**

## Index

### Constructors

* [constructor](_core_http_http_responses_.httpresponsemovedpermanently.md#constructor)

### Properties

* [body](_core_http_http_responses_.httpresponsemovedpermanently.md#body)
* [isHttpResponse](_core_http_http_responses_.httpresponsemovedpermanently.md#ishttpresponse)
* [isHttpResponseMovedPermanently](_core_http_http_responses_.httpresponsemovedpermanently.md#ishttpresponsemovedpermanently)
* [isHttpResponseRedirection](_core_http_http_responses_.httpresponsemovedpermanently.md#ishttpresponseredirection)
* [path](_core_http_http_responses_.httpresponsemovedpermanently.md#path)
* [statusCode](_core_http_http_responses_.httpresponsemovedpermanently.md#statuscode)
* [statusMessage](_core_http_http_responses_.httpresponsemovedpermanently.md#statusmessage)
* [stream](_core_http_http_responses_.httpresponsemovedpermanently.md#stream)

### Methods

* [getCookie](_core_http_http_responses_.httpresponsemovedpermanently.md#getcookie)
* [getCookies](_core_http_http_responses_.httpresponsemovedpermanently.md#getcookies)
* [getHeader](_core_http_http_responses_.httpresponsemovedpermanently.md#getheader)
* [getHeaders](_core_http_http_responses_.httpresponsemovedpermanently.md#getheaders)
* [setCookie](_core_http_http_responses_.httpresponsemovedpermanently.md#setcookie)
* [setHeader](_core_http_http_responses_.httpresponsemovedpermanently.md#setheader)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new HttpResponseMovedPermanently**(path: *`string`*): [HttpResponseMovedPermanently](_core_http_http_responses_.httpresponsemovedpermanently.md)

*Overrides [HttpResponseRedirection](_core_http_http_responses_.httpresponseredirection.md).[constructor](_core_http_http_responses_.httpresponseredirection.md#constructor)*

*Defined in [core/http/http-responses.ts:470](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L470)*

Create an instance of HttpResponseMovedPermanently.

*__memberof__*: HttpResponseMovedPermanently

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| path | `string` |  The redirection path. |

**Returns:** [HttpResponseMovedPermanently](_core_http_http_responses_.httpresponsemovedpermanently.md)

___

## Properties

<a id="body"></a>

### `<Optional>` body

**● body**: *`any`*

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[body](_core_http_http_responses_.httpresponse.md#body)*

*Defined in [core/http/http-responses.ts:77](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L77)*

___
<a id="ishttpresponse"></a>

###  isHttpResponse

**● isHttpResponse**: *`true`* = true

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[isHttpResponse](_core_http_http_responses_.httpresponse.md#ishttpresponse)*

*Defined in [core/http/http-responses.ts:42](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L42)*

Property used internally by isHttpResponse.

*__memberof__*: HttpResponse

___
<a id="ishttpresponsemovedpermanently"></a>

###  isHttpResponseMovedPermanently

**● isHttpResponseMovedPermanently**: *`true`* = true

*Defined in [core/http/http-responses.ts:468](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L468)*

Property used internally by isHttpResponseMovedPermanently.

*__memberof__*: isHttpResponseMovedPermanently

___
<a id="ishttpresponseredirection"></a>

###  isHttpResponseRedirection

**● isHttpResponseRedirection**: *`true`* = true

*Inherited from [HttpResponseRedirection](_core_http_http_responses_.httpresponseredirection.md).[isHttpResponseRedirection](_core_http_http_responses_.httpresponseredirection.md#ishttpresponseredirection)*

*Defined in [core/http/http-responses.ts:424](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L424)*

Property used internally by isHttpResponseRediction.

*__memberof__*: HttpResponseRedirection

___
<a id="path"></a>

###  path

**● path**: *`string`*

*Defined in [core/http/http-responses.ts:477](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L477)*

The redirection path.

___
<a id="statuscode"></a>

###  statusCode

**● statusCode**: *`301`* = 301

*Overrides [HttpResponse](_core_http_http_responses_.httpresponse.md).[statusCode](_core_http_http_responses_.httpresponse.md#statuscode)*

*Defined in [core/http/http-responses.ts:469](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L469)*

___
<a id="statusmessage"></a>

###  statusMessage

**● statusMessage**: *"MOVED PERMANENTLY"* = "MOVED PERMANENTLY"

*Overrides [HttpResponse](_core_http_http_responses_.httpresponse.md).[statusMessage](_core_http_http_responses_.httpresponse.md#statusmessage)*

*Defined in [core/http/http-responses.ts:470](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L470)*

___
<a id="stream"></a>

###  stream

**● stream**: *`boolean`* = false

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[stream](_core_http_http_responses_.httpresponse.md#stream)*

*Defined in [core/http/http-responses.ts:67](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L67)*

Specify if the body property is a stream.

*__type__*: {boolean}

*__memberof__*: HttpResponse

___

## Methods

<a id="getcookie"></a>

###  getCookie

▸ **getCookie**(name: *`string`*): `object`

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[getCookie](_core_http_http_responses_.httpresponse.md#getcookie)*

*Defined in [core/http/http-responses.ts:138](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L138)*

Read the value and directives of a cookie added with setCookie.

*__memberof__*: HttpResponse

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  The cookie name. |

**Returns:** `object`
)} The cookie value and directives or undefined and an empty object if the cookie does not exist.

___
<a id="getcookies"></a>

###  getCookies

▸ **getCookies**(): `object`

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[getCookies](_core_http_http_responses_.httpresponse.md#getcookies)*

*Defined in [core/http/http-responses.ts:153](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L153)*

Read all the cookies added with setCookie.

*__memberof__*: HttpResponse

**Returns:** `object`
})} The name, value and directives of the cookies.

___
<a id="getheader"></a>

###  getHeader

▸ **getHeader**(name: *`string`*): `string` \| `undefined`

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[getHeader](_core_http_http_responses_.httpresponse.md#getheader)*

*Defined in [core/http/http-responses.ts:102](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L102)*

Read the value of a header added with setHeader.

*__memberof__*: HttpResponse

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  The header name. |

**Returns:** `string` \| `undefined`
The header value or undefined if it does not exist.

___
<a id="getheaders"></a>

###  getHeaders

▸ **getHeaders**(): `object`

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[getHeaders](_core_http_http_responses_.httpresponse.md#getheaders)*

*Defined in [core/http/http-responses.ts:112](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L112)*

Read all the headers added with setHeader.

*__memberof__*: HttpResponse

**Returns:** `object`
*   The headers.

___
<a id="setcookie"></a>

###  setCookie

▸ **setCookie**(name: *`string`*, value: *`string`*, options?: *[CookieOptions](../interfaces/_core_http_http_responses_.cookieoptions.md)*): `this`

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[setCookie](_core_http_http_responses_.httpresponse.md#setcookie)*

*Defined in [core/http/http-responses.ts:125](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L125)*

Add or replace a cookie in the response.

*__memberof__*: HttpResponse

**Parameters:**

| Name | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| name | `string` | - |  The cookie name. |
| value | `string` | - |  The cookie value. |
| `Default value` options | [CookieOptions](../interfaces/_core_http_http_responses_.cookieoptions.md) |  {} |

**Returns:** `this`

___
<a id="setheader"></a>

###  setHeader

▸ **setHeader**(name: *`string`*, value: *`string`*): `this`

*Inherited from [HttpResponse](_core_http_http_responses_.httpresponse.md).[setHeader](_core_http_http_responses_.httpresponse.md#setheader)*

*Defined in [core/http/http-responses.ts:89](https://github.com/FoalTS/foal/blob/70cc46bd/packages/core/src/core/http/http-responses.ts#L89)*

Add or replace a header in the response.

*__memberof__*: HttpResponse

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` |  The header name. |
| value | `string` |  The value name. |

**Returns:** `this`

___

