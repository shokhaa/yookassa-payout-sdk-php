# [YooKassa Payout API SDK](../home.md)

# Class: \YooKassaPayout\Request\Builders\MakeDepositionRequestBuilder
### Namespace: [\YooKassaPayout\Request\Builders](../namespaces/yookassapayout-request-builders.md)
---
**Summary:**

Класс для сборки запроса MakeDepositionRequest из массива

---
### Constants
* No constants found
---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| protected | [$objectRequest](../classes/YooKassaPayout-Request-Builders-AbstractRequestBuilder.md#property_objectRequest) |  | Запрос выплаты |
---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassaPayout-Request-Builders-MakeDepositionRequestBuilder.md#method___construct) |  | MakeDepositionRequestBuilder constructor. |
| public | [build()](../classes/YooKassaPayout-Request-Builders-AbstractRequestBuilder.md#method_build) |  | Строит запрос, валидирует его и возвращает, если все прошло нормально |
| public | [setOptions()](../classes/YooKassaPayout-Request-Builders-AbstractRequestBuilder.md#method_setOptions) |  | Устанавливает свойства запроса из массива |
---
### Details
* File: [lib/Request/Builders/MakeDepositionRequestBuilder.php](../../lib/Request/Builders/MakeDepositionRequestBuilder.php)
* Package: YooKassaPayout
* Class Hierarchy: 
  * [\YooKassaPayout\Request\Builders\AbstractRequestBuilder](../classes/YooKassaPayout-Request-Builders-AbstractRequestBuilder.md)
  * \YooKassaPayout\Request\Builders\MakeDepositionRequestBuilder
---
## Properties
<a name="property_objectRequest"></a>
#### protected $objectRequest : \YooKassaPayout\Request\AbstractDepositionRequest
---
**Summary**

Запрос выплаты

**Type:** <a href="../classes/YooKassaPayout-Request-AbstractDepositionRequest.html"><abbr title="\YooKassaPayout\Request\AbstractDepositionRequest">AbstractDepositionRequest</abbr></a>

**Details:**
* Inherited From: [\YooKassaPayout\Request\Builders\AbstractRequestBuilder](../classes/YooKassaPayout-Request-Builders-AbstractRequestBuilder.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct(null|string|int $clientOrderId = null) : mixed
```

**Summary**

MakeDepositionRequestBuilder constructor.

**Details:**
* Inherited From: [\YooKassaPayout\Request\Builders\MakeDepositionRequestBuilder](../classes/YooKassaPayout-Request-Builders-MakeDepositionRequestBuilder.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">null OR string OR int</code> | clientOrderId  | Идентификатор операции |

**Returns:** mixed - 


<a name="method_build" class="anchor"></a>
#### public build() : \YooKassaPayout\Request\AbstractDepositionRequest

```php
public build(array $options = null) : \YooKassaPayout\Request\AbstractDepositionRequest
```

**Summary**

Строит запрос, валидирует его и возвращает, если все прошло нормально

**Details:**
* Inherited From: [\YooKassaPayout\Request\Builders\AbstractRequestBuilder](../classes/YooKassaPayout-Request-Builders-AbstractRequestBuilder.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">array</code> | options  | Массив свойств запроса, если нужно их установить перед сборкой |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \YooKassaPayout\Common\Exceptions\InvalidRequestException | Выбрасывается если при валидации запроса произошла ошибка массиве настроек |

**Returns:** \YooKassaPayout\Request\AbstractDepositionRequest - Инстанс собранного запроса


<a name="method_setOptions" class="anchor"></a>
#### public setOptions() : \YooKassaPayout\Request\Builders\AbstractRequestBuilder

```php
public setOptions(array|\Traversable $options) : \YooKassaPayout\Request\Builders\AbstractRequestBuilder
```

**Summary**

Устанавливает свойства запроса из массива

**Details:**
* Inherited From: [\YooKassaPayout\Request\Builders\AbstractRequestBuilder](../classes/YooKassaPayout-Request-Builders-AbstractRequestBuilder.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">array OR \Traversable</code> | options  | Массив свойств запроса |

**Returns:** \YooKassaPayout\Request\Builders\AbstractRequestBuilder - Инстанс собранного запроса



---

### Top Namespaces

* [\YooKassaPayout](../namespaces/yookassapayout.md)

---

### Reports
* [Errors - 0](../reports/errors.md)
* [Markers - 0](../reports/markers.md)
* [Deprecated - 1](../reports/deprecated.md)

---

This document was automatically generated from source code comments on 2021-12-24 using [phpDocumentor](http://www.phpdoc.org/)

&copy; 2021 YooMoney