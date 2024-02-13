# `dataExternal` Submodule <a name="`dataExternal` Submodule" id="@cdktf/provider-external.dataExternal"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataExternal <a name="DataExternal" id="@cdktf/provider-external.dataExternal.DataExternal"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external external}.

#### Initializers <a name="Initializers" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer"></a>

```python
from cdktf_cdktf_provider_external import data_external

dataExternal.DataExternal(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  program: typing.List[str],
  query: typing.Mapping[str] = None,
  working_dir: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.program">program</a></code> | <code>typing.List[str]</code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.query">query</a></code> | <code>typing.Mapping[str]</code> | A map of string values to pass to the external program as the query arguments. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.workingDir">working_dir</a></code> | <code>str</code> | Working directory of the program. If not supplied, the program will run in the current directory. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.program"></a>

- *Type:* typing.List[str]

A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.

Terraform does not execute the program through a shell, so it is not necessary to escape shell metacharacters nor add quotes around arguments containing spaces.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external#program DataExternal#program}

---

##### `query`<sup>Optional</sup> <a name="query" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.query"></a>

- *Type:* typing.Mapping[str]

A map of string values to pass to the external program as the query arguments.

If not supplied, the program will receive an empty object as its input.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external#query DataExternal#query}

---

##### `working_dir`<sup>Optional</sup> <a name="working_dir" id="@cdktf/provider-external.dataExternal.DataExternal.Initializer.parameter.workingDir"></a>

- *Type:* str

Working directory of the program. If not supplied, the program will run in the current directory.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external#working_dir DataExternal#working_dir}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toHclTerraform">to_hcl_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetQuery">reset_query</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.resetWorkingDir">reset_working_dir</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktf/provider-external.dataExternal.DataExternal.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-external.dataExternal.DataExternal.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktf/provider-external.dataExternal.DataExternal.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktf/provider-external.dataExternal.DataExternal.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_hcl_terraform` <a name="to_hcl_terraform" id="@cdktf/provider-external.dataExternal.DataExternal.toHclTerraform"></a>

```python
def to_hcl_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `to_metadata` <a name="to_metadata" id="@cdktf/provider-external.dataExternal.DataExternal.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktf/provider-external.dataExternal.DataExternal.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-external.dataExternal.DataExternal.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `reset_query` <a name="reset_query" id="@cdktf/provider-external.dataExternal.DataExternal.resetQuery"></a>

```python
def reset_query() -> None
```

##### `reset_working_dir` <a name="reset_working_dir" id="@cdktf/provider-external.dataExternal.DataExternal.resetWorkingDir"></a>

```python
def reset_working_dir() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTF code for importing a DataExternal resource upon running "cdktf plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktf/provider-external.dataExternal.DataExternal.isConstruct"></a>

```python
from cdktf_cdktf_provider_external import data_external

dataExternal.DataExternal.is_construct(
  x: typing.Any
)
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

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement"></a>

```python
from cdktf_cdktf_provider_external import data_external

dataExternal.DataExternal.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource"></a>

```python
from cdktf_cdktf_provider_external import data_external

dataExternal.DataExternal.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-external.dataExternal.DataExternal.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport"></a>

```python
from cdktf_cdktf_provider_external import data_external

dataExternal.DataExternal.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTF code for importing a DataExternal resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the DataExternal to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

The id of the existing DataExternal that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

? Optional instance of the provider where the DataExternal to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.result">result</a></code> | <code>cdktf.StringMap</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.programInput">program_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.queryInput">query_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.workingDirInput">working_dir_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.program">program</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.query">query</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.workingDir">working_dir</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-external.dataExternal.DataExternal.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktf/provider-external.dataExternal.DataExternal.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-external.dataExternal.DataExternal.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktf/provider-external.dataExternal.DataExternal.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktf/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-external.dataExternal.DataExternal.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-external.dataExternal.DataExternal.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-external.dataExternal.DataExternal.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-external.dataExternal.DataExternal.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-external.dataExternal.DataExternal.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-external.dataExternal.DataExternal.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `result`<sup>Required</sup> <a name="result" id="@cdktf/provider-external.dataExternal.DataExternal.property.result"></a>

```python
result: StringMap
```

- *Type:* cdktf.StringMap

---

##### `program_input`<sup>Optional</sup> <a name="program_input" id="@cdktf/provider-external.dataExternal.DataExternal.property.programInput"></a>

```python
program_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `query_input`<sup>Optional</sup> <a name="query_input" id="@cdktf/provider-external.dataExternal.DataExternal.property.queryInput"></a>

```python
query_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `working_dir_input`<sup>Optional</sup> <a name="working_dir_input" id="@cdktf/provider-external.dataExternal.DataExternal.property.workingDirInput"></a>

```python
working_dir_input: str
```

- *Type:* str

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktf/provider-external.dataExternal.DataExternal.property.program"></a>

```python
program: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `query`<sup>Required</sup> <a name="query" id="@cdktf/provider-external.dataExternal.DataExternal.property.query"></a>

```python
query: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `working_dir`<sup>Required</sup> <a name="working_dir" id="@cdktf/provider-external.dataExternal.DataExternal.property.workingDir"></a>

```python
working_dir: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternal.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-external.dataExternal.DataExternal.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataExternalConfig <a name="DataExternalConfig" id="@cdktf/provider-external.dataExternal.DataExternalConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-external.dataExternal.DataExternalConfig.Initializer"></a>

```python
from cdktf_cdktf_provider_external import data_external

dataExternal.DataExternalConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  program: typing.List[str],
  query: typing.Mapping[str] = None,
  working_dir: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.program">program</a></code> | <code>typing.List[str]</code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.query">query</a></code> | <code>typing.Mapping[str]</code> | A map of string values to pass to the external program as the query arguments. |
| <code><a href="#@cdktf/provider-external.dataExternal.DataExternalConfig.property.workingDir">working_dir</a></code> | <code>str</code> | Working directory of the program. If not supplied, the program will run in the current directory. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.program"></a>

```python
program: typing.List[str]
```

- *Type:* typing.List[str]

A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.

Terraform does not execute the program through a shell, so it is not necessary to escape shell metacharacters nor add quotes around arguments containing spaces.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external#program DataExternal#program}

---

##### `query`<sup>Optional</sup> <a name="query" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.query"></a>

```python
query: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

A map of string values to pass to the external program as the query arguments.

If not supplied, the program will receive an empty object as its input.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external#query DataExternal#query}

---

##### `working_dir`<sup>Optional</sup> <a name="working_dir" id="@cdktf/provider-external.dataExternal.DataExternalConfig.property.workingDir"></a>

```python
working_dir: str
```

- *Type:* str

Working directory of the program. If not supplied, the program will run in the current directory.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.3.3/docs/data-sources/external#working_dir DataExternal#working_dir}

---



