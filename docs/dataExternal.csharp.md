# `dataExternal` Submodule <a name="`dataExternal` Submodule" id="@cdktf/provider-external.dataExternal"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataExternal <a name="DataExternal" id="@cdktf/provider-external.dataExternal.DataExternal"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/external/2.3.5/docs/data-sources/external external}.

#### Initializers <a name="Initializers" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.External;

new DataExternal(Construct Scope, string Id, DataExternalConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig">DataExternalConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-external.dataExternal.DataExternalConfig">DataExternalConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toHclTerraform">ToHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetQuery">ResetQuery</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetWorkingDir">ResetWorkingDir</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-external.dataExternal.DataExternal.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-external.dataExternal.DataExternal.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktf/provider-external.dataExternal.DataExternal.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-external.dataExternal.DataExternal.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-external.dataExternal.DataExternal.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ResetQuery` <a name="ResetQuery" id="@cdktf/provider-external.dataExternal.DataExternal.resetQuery"></a>

```csharp
private void ResetQuery()
```

##### `ResetWorkingDir` <a name="ResetWorkingDir" id="@cdktf/provider-external.dataExternal.DataExternal.resetWorkingDir"></a>

```csharp
private void ResetWorkingDir()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTF code for importing a DataExternal resource upon running "cdktf plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-external.dataExternal.DataExternal.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.External;

DataExternal.IsConstruct(object X);
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-external.dataExternal.DataExternal.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.External;

DataExternal.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource"></a>

```csharp
using HashiCorp.Cdktf.Providers.External;

DataExternal.IsTerraformDataSource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport"></a>

```csharp
using HashiCorp.Cdktf.Providers.External;

DataExternal.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTF code for importing a DataExternal resource upon running "cdktf plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the DataExternal to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing DataExternal that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/external/2.3.5/docs/data-sources/external#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.provider"></a>

- *Type:* HashiCorp.Cdktf.TerraformProvider

? Optional instance of the provider where the DataExternal to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.count">Count</a></code> | <code>double\|HashiCorp.Cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.result">Result</a></code> | <code>HashiCorp.Cdktf.StringMap</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.programInput">ProgramInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.queryInput">QueryInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.workingDirInput">WorkingDirInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.program">Program</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.query">Query</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.workingDir">WorkingDir</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-external.dataExternal.DataExternal.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-external.dataExternal.DataExternal.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-external.dataExternal.DataExternal.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-external.dataExternal.DataExternal.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-external.dataExternal.DataExternal.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|HashiCorp.Cdktf.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-external.dataExternal.DataExternal.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-external.dataExternal.DataExternal.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-external.dataExternal.DataExternal.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-external.dataExternal.DataExternal.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-external.dataExternal.DataExternal.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Result`<sup>Required</sup> <a name="Result" id="@cdktf/provider-external.dataExternal.DataExternal.property.result"></a>

```csharp
public StringMap Result { get; }
```

- *Type:* HashiCorp.Cdktf.StringMap

---

##### `ProgramInput`<sup>Optional</sup> <a name="ProgramInput" id="@cdktf/provider-external.dataExternal.DataExternal.property.programInput"></a>

```csharp
public string[] ProgramInput { get; }
```

- *Type:* string[]

---

##### `QueryInput`<sup>Optional</sup> <a name="QueryInput" id="@cdktf/provider-external.dataExternal.DataExternal.property.queryInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> QueryInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `WorkingDirInput`<sup>Optional</sup> <a name="WorkingDirInput" id="@cdktf/provider-external.dataExternal.DataExternal.property.workingDirInput"></a>

```csharp
public string WorkingDirInput { get; }
```

- *Type:* string

---

##### `Program`<sup>Required</sup> <a name="Program" id="@cdktf/provider-external.dataExternal.DataExternal.property.program"></a>

```csharp
public string[] Program { get; }
```

- *Type:* string[]

---

##### `Query`<sup>Required</sup> <a name="Query" id="@cdktf/provider-external.dataExternal.DataExternal.property.query"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Query { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `WorkingDir`<sup>Required</sup> <a name="WorkingDir" id="@cdktf/provider-external.dataExternal.DataExternal.property.workingDir"></a>

```csharp
public string WorkingDir { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-external.dataExternal.DataExternal.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataExternalConfig <a name="DataExternalConfig" id="@cdktf/provider-external.dataExternal.DataExternalConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-external.dataExternal.DataExternalConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.External;

new DataExternalConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string[] Program,
    System.Collections.Generic.IDictionary<string, string> Query = null,
    string WorkingDir = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.connection">Connection</a></code> | <code>HashiCorp.Cdktf.SSHProvisionerConnection\|HashiCorp.Cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.count">Count</a></code> | <code>double\|HashiCorp.Cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.provisioners">Provisioners</a></code> | <code>HashiCorp.Cdktf.FileProvisioner\|HashiCorp.Cdktf.LocalExecProvisioner\|HashiCorp.Cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.program">Program</a></code> | <code>string[]</code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.query">Query</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | A map of string values to pass to the external program as the query arguments. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.workingDir">WorkingDir</a></code> | <code>string</code> | Working directory of the program. If not supplied, the program will run in the current directory. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* HashiCorp.Cdktf.SSHProvisionerConnection|HashiCorp.Cdktf.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|HashiCorp.Cdktf.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* HashiCorp.Cdktf.FileProvisioner|HashiCorp.Cdktf.LocalExecProvisioner|HashiCorp.Cdktf.RemoteExecProvisioner[]

---

##### `Program`<sup>Required</sup> <a name="Program" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.program"></a>

```csharp
public string[] Program { get; set; }
```

- *Type:* string[]

A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.

Terraform does not execute the program through a shell, so it is not necessary to escape shell metacharacters nor add quotes around arguments containing spaces.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.5/docs/data-sources/external#program DataExternal#program}

---

##### `Query`<sup>Optional</sup> <a name="Query" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.query"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Query { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

A map of string values to pass to the external program as the query arguments.

If not supplied, the program will receive an empty object as its input.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.5/docs/data-sources/external#query DataExternal#query}

---

##### `WorkingDir`<sup>Optional</sup> <a name="WorkingDir" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.workingDir"></a>

```csharp
public string WorkingDir { get; set; }
```

- *Type:* string

Working directory of the program. If not supplied, the program will run in the current directory.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.5/docs/data-sources/external#working_dir DataExternal#working_dir}

---



