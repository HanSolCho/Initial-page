---
description: 본 화면은 API 문서 작성을 위한 테스트화면입니다.
---

# API 문서 테스트



{% api-method method="get" host="domain" path="/경로" %}
{% api-method-summary %}
configuraionInfo
{% endapi-method-summary %}

{% api-method-description %}
해당 api는 get방식이지만 body에 메세지가 담길경우....
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Authentication token to track down who is emptying our stocks.
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-query-parameters %}
{% api-method-parameter name="ver" type="string" required=false %}
3.1.1
{% endapi-method-parameter %}

{% api-method-parameter name="id" type="integer" %}
3
{% endapi-method-parameter %}

{% api-method-parameter name="id2" type="string" %}
asdasdsfafdw
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Cake sucddcessfully retrieved.
{% endapi-method-response-example-description %}

```text
{    "name": "Cake's name",    "recipe": "Cake's recipe name",    "cake": "Binary cake"}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not find a cake matching this query.
{% endapi-method-response-example-description %}

```text
{    "message": "Ain't no cake like that."}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=500 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{ "message" : ":tet"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

