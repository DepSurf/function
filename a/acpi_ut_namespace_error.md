# Function: <code>acpi_ut_namespace_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ut_namespace_error(const char *module_name, u32 line_number, const char *internal_name, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff814a795c)
Location: drivers/acpi/acpica/uterror.c:199
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff814a795c-ffffffff814a7a45: acpi_ut_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ut_namespace_error(const char *module_name, u32 line_number, const char *internal_name, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff814f6cdc)
Location: drivers/acpi/acpica/uterror.c:199
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
ffffffff814f6cdc-ffffffff814f6dc5: acpi_ut_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ut_namespace_error(const char *module_name, u32 line_number, const char *internal_name, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8151989f)
Location: drivers/acpi/acpica/uterror.c:199
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
ffffffff8151989f-ffffffff81519988: acpi_ut_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ut_namespace_error(const char *module_name, u32 line_number, const char *internal_name, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8152a0cf)
Location: drivers/acpi/acpica/uterror.c:199
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
ffffffff8152a0cf-ffffffff8152a1b8: acpi_ut_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ut_namespace_error(const char *module_name, u32 line_number, const char *internal_name, acpi_status lookup_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8158317f)
Location: drivers/acpi/acpica/uterror.c:199
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
ffffffff8158317f-ffffffff81583268: acpi_ut_namespace_error (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
