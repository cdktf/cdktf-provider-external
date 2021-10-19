# API Reference

**Classes**

Name|Description
----|-----------
[DataExternal](#cdktf-provider-external-dataexternal)|Represents a {@link https://www.terraform.io/docs/providers/external/d/external.html external}.
[ExternalProvider](#cdktf-provider-external-externalprovider)|Represents a {@link https://www.terraform.io/docs/providers/external external}.


**Structs**

Name|Description
----|-----------
[DataExternalConfig](#cdktf-provider-external-dataexternalconfig)|*No description*
[ExternalProviderConfig](#cdktf-provider-external-externalproviderconfig)|*No description*



## class DataExternal  <a id="cdktf-provider-external-dataexternal"></a>

Represents a {@link https://www.terraform.io/docs/providers/external/d/external.html external}.

__Implements__: [IConstruct](#constructs-iconstruct), [IDependable](#constructs-idependable), [ITerraformResource](#cdktf-iterraformresource), [ITerraformDependable](#cdktf-iterraformdependable)
__Extends__: [TerraformDataSource](#cdktf-terraformdatasource)

### Initializer


Create a new {@link https://www.terraform.io/docs/providers/external/d/external.html external} Data Source.

```ts
new DataExternal(scope: Construct, id: string, config: DataExternalConfig)
```

* **scope** (<code>[Construct](#constructs-construct)</code>)  The scope in which to define this construct.
* **id** (<code>string</code>)  The scoped construct ID.
* **config** (<code>[DataExternalConfig](#cdktf-provider-external-dataexternalconfig)</code>)  *No description*
  * **count** (<code>number &#124; [IResolvable](#cdktf-iresolvable)</code>)  *No description* __*Optional*__
  * **dependsOn** (<code>Array<[ITerraformDependable](#cdktf-iterraformdependable)></code>)  *No description* __*Optional*__
  * **lifecycle** (<code>[TerraformResourceLifecycle](#cdktf-terraformresourcelifecycle)</code>)  *No description* __*Optional*__
  * **provider** (<code>[TerraformProvider](#cdktf-terraformprovider)</code>)  *No description* __*Optional*__
  * **program** (<code>Array<string></code>)  A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. 
  * **query** (<code>Map<string, string> &#124; [IResolvable](#cdktf-iresolvable)</code>)  A map of string values to pass to the external program as the query arguments. __*Optional*__
  * **workingDir** (<code>string</code>)  Working directory of the program. If not supplied, the program will run in the current directory. __*Optional*__



### Properties


Name | Type | Description 
-----|------|-------------
**id** | <code>string</code> | <span></span>
**program** | <code>Array<string></code> | <span></span>
**programInput**? | <code>Array<string></code> | __*Optional*__
**query**? | <code>[IResolvable](#cdktf-iresolvable) &#124; Map<string, string></code> | __*Optional*__
**queryInput**? | <code>[IResolvable](#cdktf-iresolvable) &#124; Map<string, string></code> | __*Optional*__
**workingDir**? | <code>string</code> | __*Optional*__
**workingDirInput**? | <code>string</code> | __*Optional*__
*static* **tfResourceType** | <code>string</code> | <span></span>

### Methods


#### resetQuery() <a id="cdktf-provider-external-dataexternal-resetquery"></a>



```ts
resetQuery(): void
```





#### resetWorkingDir() <a id="cdktf-provider-external-dataexternal-resetworkingdir"></a>



```ts
resetWorkingDir(): void
```





#### result(key) <a id="cdktf-provider-external-dataexternal-result"></a>



```ts
result(key: string): string
```

* **key** (<code>string</code>)  *No description*

__Returns__:
* <code>string</code>

#### protected synthesizeAttributes() <a id="cdktf-provider-external-dataexternal-synthesizeattributes"></a>



```ts
protected synthesizeAttributes(): Map<string, any>
```


__Returns__:
* <code>Map<string, any></code>



## class ExternalProvider  <a id="cdktf-provider-external-externalprovider"></a>

Represents a {@link https://www.terraform.io/docs/providers/external external}.

__Implements__: [IConstruct](#constructs-iconstruct), [IDependable](#constructs-idependable)
__Extends__: [TerraformProvider](#cdktf-terraformprovider)

### Initializer


Create a new {@link https://www.terraform.io/docs/providers/external external} Resource.

```ts
new ExternalProvider(scope: Construct, id: string, config?: ExternalProviderConfig)
```

* **scope** (<code>[Construct](#constructs-construct)</code>)  The scope in which to define this construct.
* **id** (<code>string</code>)  The scoped construct ID.
* **config** (<code>[ExternalProviderConfig](#cdktf-provider-external-externalproviderconfig)</code>)  *No description*
  * **alias** (<code>string</code>)  Alias name. __*Optional*__



### Properties


Name | Type | Description 
-----|------|-------------
**alias**? | <code>string</code> | __*Optional*__
**aliasInput**? | <code>string</code> | __*Optional*__
*static* **tfResourceType** | <code>string</code> | <span></span>

### Methods


#### resetAlias() <a id="cdktf-provider-external-externalprovider-resetalias"></a>



```ts
resetAlias(): void
```





#### protected synthesizeAttributes() <a id="cdktf-provider-external-externalprovider-synthesizeattributes"></a>



```ts
protected synthesizeAttributes(): Map<string, any>
```


__Returns__:
* <code>Map<string, any></code>



## struct DataExternalConfig  <a id="cdktf-provider-external-dataexternalconfig"></a>






Name | Type | Description 
-----|------|-------------
**program** | <code>Array<string></code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.
**count**?🔹 | <code>number &#124; [IResolvable](#cdktf-iresolvable)</code> | __*Optional*__
**dependsOn**?🔹 | <code>Array<[ITerraformDependable](#cdktf-iterraformdependable)></code> | __*Optional*__
**lifecycle**?🔹 | <code>[TerraformResourceLifecycle](#cdktf-terraformresourcelifecycle)</code> | __*Optional*__
**provider**?🔹 | <code>[TerraformProvider](#cdktf-terraformprovider)</code> | __*Optional*__
**query**? | <code>Map<string, string> &#124; [IResolvable](#cdktf-iresolvable)</code> | A map of string values to pass to the external program as the query arguments.<br/>__*Optional*__
**workingDir**? | <code>string</code> | Working directory of the program. If not supplied, the program will run in the current directory.<br/>__*Optional*__



## struct ExternalProviderConfig  <a id="cdktf-provider-external-externalproviderconfig"></a>






Name | Type | Description 
-----|------|-------------
**alias**? | <code>string</code> | Alias name.<br/>__*Optional*__



