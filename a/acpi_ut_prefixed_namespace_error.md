# Function: <code>acpi_ut_prefixed_namespace_error</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815ba331)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815ba331-ffffffff815ba405: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815d378b)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815d378b-ffffffff815d385f: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81605108)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff81605108-ffffffff816051e2: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816265b2)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff816265b2-ffffffff8162668c: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816d2d62)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff816d2d62-ffffffff816d2e3c: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816f0d40)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff816f0d40-ffffffff816f0e1a: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816d2bea)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff816d2bea-ffffffff816d2cc1: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8174a42e)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8174a42e-ffffffff8174a505: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8187c8a5)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8187c8a5-ffffffff8187c99a: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff819bfe70)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff819bfe70-ffffffff819bff83: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81a07070)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff81a07070-ffffffff81a07183: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81a51f10)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff81a51f10-ffffffff81a52023: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
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
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffff80001079ba84)
Location: drivers/acpi/acpica/uterror.c:168
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffff80001079ba84-ffff80001079bb84: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
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
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815fee14)
Location: drivers/acpi/acpica/uterror.c:168
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815fee14-ffffffff815feeee: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815ea30b)
Location: drivers/acpi/acpica/uterror.c:168
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815ea30b-ffffffff815ea3e5: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8161a892)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8161a892-ffffffff8161a96c: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_prefixed_namespace_error(const char *module_name, u32 line_number, union acpi_generic_state *prefix_scope, const char *internal_path, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81634742)
Location: drivers/acpi/acpica/uterror.c:168
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
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff81634742-ffffffff8163481c: acpi_ut_prefixed_namespace_error (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
