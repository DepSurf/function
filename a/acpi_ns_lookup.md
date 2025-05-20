# Function: <code>acpi_ns_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff8149bbb3)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8149bbb3-ffffffff8149bf31: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff814eac2d)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff814eac2d-ffffffff814eafb1: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff8150d4b5)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8150d4b5-ffffffff8150d839: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff8151db88)
Location: drivers/acpi/acpica/nsaccess.c:285
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8151db88-ffffffff8151deec: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff8156ebfa)
Location: drivers/acpi/acpica/nsaccess.c:285
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff8156ebfa-ffffffff8156f403: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff815a58da)
Location: drivers/acpi/acpica/nsaccess.c:249
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff815a58da-ffffffff815a60de: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff815be5ce)
Location: drivers/acpi/acpica/nsaccess.c:249
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff815be5ce-ffffffff815bee23: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f0568)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff815f0568-ffffffff815f0dce: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff816119f6)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816119f6-ffffffff8161225c: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff816bdf27)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816bdf27-ffffffff816be789: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff816dba95)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816dba95-ffffffff816dc2f7: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff816bd970)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816bd970-ffffffff816be1cf: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff81734bff)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff81734bff-ffffffff8173545e: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff81865c55)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff81865c55-ffffffff8186649e: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff819a3f50)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff819a3f50-ffffffff819a4981: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff819eac00)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff819eac00-ffffffff819eb657: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff81a359c0)
Location: drivers/acpi/acpica/nsaccess.c:280
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff81a359c0-ffffffff81a36417: acpi_ns_lookup (STB_GLOBAL)
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
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffff80001078bd40)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffff80001078bd40-ffff80001078c168: acpi_ns_lookup (STB_GLOBAL)
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
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f21e6)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815f21e6-ffffffff815f25c7: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff815dd779)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815dd779-ffffffff815ddb5a: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff81605cd6)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff81605cd6-ffffffff8160653c: acpi_ns_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state *scope_info, char *pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state *walk_state, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsaccess.c (ffffffff8161fb86)
Location: drivers/acpi/acpica/nsaccess.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff8161fb86-ffffffff816203ec: acpi_ns_lookup (STB_GLOBAL)
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
