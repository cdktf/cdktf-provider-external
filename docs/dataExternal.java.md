# `dataExternal` Submodule <a name="`dataExternal` Submodule" id="@cdktf/provider-external.dataExternal"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataExternal <a name="DataExternal" id="@cdktf/provider-external.dataExternal.DataExternal"></a>

Represents a {@link https://www.terraform.io/docs/providers/external/d/external external}.

#### Initializers <a name="Initializers" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.external.data_external.DataExternal;

DataExternal.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection)
//  .connection(WinrmProvisionerConnection)
//  .count(java.lang.Number)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner)
//  .provisioners(LocalExecProvisioner)
//  .provisioners(RemoteExecProvisioner>)
    .program(java.util.List<java.lang.String>)
//  .id(java.lang.String)
//  .query(java.util.Map<java.lang.String, java.lang.String>)
//  .workingDir(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.count">count</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.program">program</a></code> | <code>java.util.List<java.lang.String></code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#id DataExternal#id}. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.query">query</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of string values to pass to the external program as the query arguments. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.workingDir">workingDir</a></code> | <code>java.lang.String</code> | Working directory of the program. If not supplied, the program will run in the current directory. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.count"></a>

- *Type:* java.lang.Number

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.program"></a>

- *Type:* java.util.List<java.lang.String>

A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.

Terraform does not execute the program through a shell, so it is not necessary to escape shell metacharacters nor add quotes around arguments containing spaces.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#program DataExternal#program}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#id DataExternal#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `query`<sup>Optional</sup> <a name="query" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.query"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of string values to pass to the external program as the query arguments.

If not supplied, the program will receive an empty object as its input.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#query DataExternal#query}

---

##### `workingDir`<sup>Optional</sup> <a name="workingDir" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.workingDir"></a>

- *Type:* java.lang.String

Working directory of the program. If not supplied, the program will run in the current directory.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#working_dir DataExternal#working_dir}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetId">resetId</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetQuery">resetQuery</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetWorkingDir">resetWorkingDir</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktf/provider-external.dataExternal.DataExternal.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktf/provider-external.dataExternal.DataExternal.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="@cdktf/provider-external.dataExternal.DataExternal.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktf/provider-external.dataExternal.DataExternal.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `resetId` <a name="resetId" id="@cdktf/provider-external.dataExternal.DataExternal.resetId"></a>

```java
public void resetId()
```

##### `resetQuery` <a name="resetQuery" id="@cdktf/provider-external.dataExternal.DataExternal.resetQuery"></a>

```java
public void resetQuery()
```

##### `resetWorkingDir` <a name="resetWorkingDir" id="@cdktf/provider-external.dataExternal.DataExternal.resetWorkingDir"></a>

```java
public void resetWorkingDir()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="@cdktf/provider-external.dataExternal.DataExternal.isConstruct"></a>

```java
import com.hashicorp.cdktf.providers.external.data_external.DataExternal;

DataExternal.isConstruct(java.lang.Object x)
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-external.dataExternal.DataExternal.isConstruct.parameter.x"></a>

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.external.data_external.DataExternal;

DataExternal.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource"></a>

```java
import com.hashicorp.cdktf.providers.external.data_external.DataExternal;

DataExternal.isTerraformDataSource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource.parameter.x"></a>

- *Type:* java.lang.Object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.count">count</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.result">result</a></code> | <code>com.hashicorp.cdktf.StringMap</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.programInput">programInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.queryInput">queryInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.workingDirInput">workingDirInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.program">program</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.query">query</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.workingDir">workingDir</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-external.dataExternal.DataExternal.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktf/provider-external.dataExternal.DataExternal.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-external.dataExternal.DataExternal.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktf/provider-external.dataExternal.DataExternal.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-external.dataExternal.DataExternal.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-external.dataExternal.DataExternal.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-external.dataExternal.DataExternal.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-external.dataExternal.DataExternal.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-external.dataExternal.DataExternal.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `result`<sup>Required</sup> <a name="result" id="@cdktf/provider-external.dataExternal.DataExternal.property.result"></a>

```java
public StringMap getResult();
```

- *Type:* com.hashicorp.cdktf.StringMap

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktf/provider-external.dataExternal.DataExternal.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `programInput`<sup>Optional</sup> <a name="programInput" id="@cdktf/provider-external.dataExternal.DataExternal.property.programInput"></a>

```java
public java.util.List<java.lang.String> getProgramInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `queryInput`<sup>Optional</sup> <a name="queryInput" id="@cdktf/provider-external.dataExternal.DataExternal.property.queryInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getQueryInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `workingDirInput`<sup>Optional</sup> <a name="workingDirInput" id="@cdktf/provider-external.dataExternal.DataExternal.property.workingDirInput"></a>

```java
public java.lang.String getWorkingDirInput();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-external.dataExternal.DataExternal.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktf/provider-external.dataExternal.DataExternal.property.program"></a>

```java
public java.util.List<java.lang.String> getProgram();
```

- *Type:* java.util.List<java.lang.String>

---

##### `query`<sup>Required</sup> <a name="query" id="@cdktf/provider-external.dataExternal.DataExternal.property.query"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getQuery();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `workingDir`<sup>Required</sup> <a name="workingDir" id="@cdktf/provider-external.dataExternal.DataExternal.property.workingDir"></a>

```java
public java.lang.String getWorkingDir();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-external.dataExternal.DataExternal.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### DataExternalConfig <a name="DataExternalConfig" id="@cdktf/provider-external.dataExternal.DataExternalConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-external.dataExternal.DataExternalConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.external.data_external.DataExternalConfig;

DataExternalConfig.builder()
//  .connection(SSHProvisionerConnection)
//  .connection(WinrmProvisionerConnection)
//  .count(java.lang.Number)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner)
//  .provisioners(LocalExecProvisioner)
//  .provisioners(RemoteExecProvisioner>)
    .program(java.util.List<java.lang.String>)
//  .id(java.lang.String)
//  .query(java.util.Map<java.lang.String, java.lang.String>)
//  .workingDir(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.count">count</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.program">program</a></code> | <code>java.util.List<java.lang.String></code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#id DataExternal#id}. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.query">query</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of string values to pass to the external program as the query arguments. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.workingDir">workingDir</a></code> | <code>java.lang.String</code> | Working directory of the program. If not supplied, the program will run in the current directory. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.program"></a>

```java
public java.util.List<java.lang.String> getProgram();
```

- *Type:* java.util.List<java.lang.String>

A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.

Terraform does not execute the program through a shell, so it is not necessary to escape shell metacharacters nor add quotes around arguments containing spaces.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#program DataExternal#program}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#id DataExternal#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `query`<sup>Optional</sup> <a name="query" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.query"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getQuery();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of string values to pass to the external program as the query arguments.

If not supplied, the program will receive an empty object as its input.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#query DataExternal#query}

---

##### `workingDir`<sup>Optional</sup> <a name="workingDir" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.workingDir"></a>

```java
public java.lang.String getWorkingDir();
```

- *Type:* java.lang.String

Working directory of the program. If not supplied, the program will run in the current directory.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/external/d/external#working_dir DataExternal#working_dir}

---



