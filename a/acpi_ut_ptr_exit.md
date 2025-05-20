# Function: <code>acpi_ut_ptr_exit</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81582113)
Location: drivers/acpi/acpica/utdebug.c:544
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81582113-ffffffff8158217c: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b92c8)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff815b92c8-ffffffff815b9331: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d2699)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff815d2699-ffffffff815d2702: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603f8d)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81603f8d-ffffffff81603ffb: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81625437)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81625437-ffffffff816254a5: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1bdb)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816d1bdb-ffffffff816d1c4a: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816efbb9)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816efbb9-ffffffff816efc28: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1a1e)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816d1a1e-ffffffff816d1a8d: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81749178)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81749178-ffffffff817491e7: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187b425)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff8187b425-ffffffff8187b4cc: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819be4b0)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff819be4b0-ffffffff819be557: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a056a0)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81a056a0-ffffffff81a05747: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a50540)
Location: drivers/acpi/acpica/utdebug.c:529
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81a50540-ffffffff81a505e7: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81619717)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81619717-ffffffff81619785: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u8 *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816335c7)
Location: drivers/acpi/acpica/utdebug.c:524
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816335c7-ffffffff81633635: acpi_ut_ptr_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
