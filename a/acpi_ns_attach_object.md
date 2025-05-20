# Function: <code>acpi_ns_attach_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8149d608)
Location: drivers/acpi/acpica/nsobject.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
**Symbols:**

```
ffffffff8149d608-ffffffff8149d71a: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff814ec84e)
Location: drivers/acpi/acpica/nsobject.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
**Symbols:**

```
ffffffff814ec84e-ffffffff814ec960: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8150f10f)
Location: drivers/acpi/acpica/nsobject.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
**Symbols:**

```
ffffffff8150f10f-ffffffff8150f221: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8151f7e5)
Location: drivers/acpi/acpica/nsobject.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
**Symbols:**

```
ffffffff8151f7e5-ffffffff8151f8e5: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81572715)
Location: drivers/acpi/acpica/nsobject.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
**Symbols:**

```
ffffffff81572715-ffffffff81572960: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815a9682)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
**Symbols:**

```
ffffffff815a9682-ffffffff815a98cd: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815c252a)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
**Symbols:**

```
ffffffff815c252a-ffffffff815c2775: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815f3f1c)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815f3f1c-ffffffff815f4168: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816153bb)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff816153bb-ffffffff81615607: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816c18dc)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff816c18dc-ffffffff816c1b28: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816df444)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff816df444-ffffffff816df690: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816c132f)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff816c132f-ffffffff816c157b: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8173861c)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff8173861c-ffffffff81738868: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff818699bb)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
**Symbols:**

```
ffffffff818699bb-ffffffff81869c5e: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff819a89b0)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
**Symbols:**

```
ffffffff819a89b0-ffffffff819a8cb5: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff819ef860)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
**Symbols:**

```
ffffffff819ef860-ffffffff819efb65: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81a3a650)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
**Symbols:**

```
ffffffff81a3a650-ffffffff81a3a955: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffff80001078de6c)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffff80001078de6c-ffff80001078df8c: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815f3d78)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815f3d78-ffffffff815f3e6d: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815df2fc)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff815df2fc-ffffffff815df3f1: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8160969b)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff8160969b-ffffffff816098e7: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node *node, union acpi_operand_object *object, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8162354b)
Location: drivers/acpi/acpica/nsobject.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
**Symbols:**

```
ffffffff8162354b-ffffffff81623797: acpi_ns_attach_object (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
