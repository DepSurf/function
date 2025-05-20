# Function: <code>acpi_ut_value_exit</code>

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
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81581cee)
Location: drivers/acpi/acpica/utdebug.c:505
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff81581cee-ffffffff81581d5e: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b8ea7)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff815b8ea7-ffffffff815b8f17: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d2278)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff815d2278-ffffffff815d22e8: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603b70)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff81603b70-ffffffff81603be6: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8162501a)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff8162501a-ffffffff81625090: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d17b5)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff816d17b5-ffffffff816d182c: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816ef793)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff816ef793-ffffffff816ef80a: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d15f8)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff816d15f8-ffffffff816d166f: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81748d52)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff81748d52-ffffffff81748dc9: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187af0b)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff8187af0b-ffffffff8187afba: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819bdd80)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff819bdd80-ffffffff819bde31: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a04f70)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff81a04f70-ffffffff81a05021: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a4fe10)
Location: drivers/acpi/acpica/utdebug.c:490
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff81a4fe10-ffffffff81a4fec1: acpi_ut_value_exit (STB_GLOBAL)
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
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816192fa)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff816192fa-ffffffff81619370: acpi_ut_value_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816331aa)
Location: drivers/acpi/acpica/utdebug.c:485
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
```
**Symbols:**

```
ffffffff816331aa-ffffffff81633220: acpi_ut_value_exit (STB_GLOBAL)
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
