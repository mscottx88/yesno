[yesno-http](../README.md) > ["filtering/collection"](../modules/_filtering_collection_.md) > [IFiltered](../interfaces/_filtering_collection_.ifiltered.md)

# Interface: IFiltered

## Hierarchy

**IFiltered**

## Implemented by

* [FilteredHttpCollection](../classes/_filtering_collection_.filteredhttpcollection.md)
* [YesNo](../classes/_yesno_.yesno.md)

## Index

### Properties

* [intercepted](_filtering_collection_.ifiltered.md#intercepted)
* [mocks](_filtering_collection_.ifiltered.md#mocks)
* [redact](_filtering_collection_.ifiltered.md#redact)

---

## Properties

<a id="intercepted"></a>

###  intercepted

**● intercepted**: *`function`*

#### Type declaration
▸(): [ISerializedHttp](_http_serializer_.iserializedhttp.md)[]

**Returns:** [ISerializedHttp](_http_serializer_.iserializedhttp.md)[]

___
<a id="mocks"></a>

###  mocks

**● mocks**: *`function`*

#### Type declaration
▸(): [ISerializedHttp](_http_serializer_.iserializedhttp.md)[]

**Returns:** [ISerializedHttp](_http_serializer_.iserializedhttp.md)[]

___
<a id="redact"></a>

###  redact

**● redact**: *`function`*

#### Type declaration
▸(property: * `string` &#124; `string`[]*, symbol: *[Redactor](../modules/_filtering_redact_.md#redactor)*): `void`

**Parameters:**

| Name | Type |
| ------ | ------ |
| property |  `string` &#124; `string`[]|
| symbol | [Redactor](../modules/_filtering_redact_.md#redactor) |

**Returns:** `void`

___

