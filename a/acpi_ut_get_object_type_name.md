# Function: <code>acpi_ut_get_object_type_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814a712a)
Location: drivers/acpi/acpica/utdecode.c:233
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff814a712a-ffffffff814a716b: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814f64ad)
Location: drivers/acpi/acpica/utdecode.c:234
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff814f64ad-ffffffff814f64ee: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81519070)
Location: drivers/acpi/acpica/utdecode.c:235
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81519070-ffffffff815190b1: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81529886)
Location: drivers/acpi/acpica/utdecode.c:235
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
**Symbols:**

```
ffffffff81529886-ffffffff815298c7: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815822eb)
Location: drivers/acpi/acpica/utdecode.c:235
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff815822eb-ffffffff81582453: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815b94a0)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff815b94a0-ffffffff815b9608: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815d2871)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff815d2871-ffffffff815d29d9: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81604173)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81604173-ffffffff816042da: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8162561d)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff8162561d-ffffffff81625784: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1dc3)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816d1dc3-ffffffff816d1f22: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816efda1)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816efda1-ffffffff816eff00: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1c06)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816d1c06-ffffffff816d1d65: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff817493b0)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff817493b0-ffffffff81749509: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8187b715)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff8187b715-ffffffff8187b880: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff819be780)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff819be780-ffffffff819be989: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a05970)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81a05970-ffffffff81a05b79: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a50810)
Location: drivers/acpi/acpica/utdecode.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81a50810-ffffffff81a50a19: acpi_ut_get_object_type_name (STB_GLOBAL)
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
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffff80001079afd8)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffff80001079afd8-ffff80001079b050: acpi_ut_get_object_type_name (STB_GLOBAL)
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
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815fe4fd)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff815fe4fd-ffffffff815fe53e: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815e99f4)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff815e99f4-ffffffff815e9a35: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816198fd)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816198fd-ffffffff81619a64: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *acpi_ut_get_object_type_name(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816337ad)
Location: drivers/acpi/acpica/utdecode.c:201
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816337ad-ffffffff81633914: acpi_ut_get_object_type_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>const char *</code>
</li>
</ul>
</details>
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
