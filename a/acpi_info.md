# Function: <code>acpi_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_info(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814aa68c)
Location: drivers/acpi/acpica/utxferror.c:178
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff814aa68c-ffffffff814aa71a: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814f98da)
Location: drivers/acpi/acpica/utxferror.c:178
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff814f98da-ffffffff814f9970: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8151c45d)
Location: drivers/acpi/acpica/utxferror.c:178
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff8151c45d-ffffffff8151c4f3: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8152cc68)
Location: drivers/acpi/acpica/utxferror.c:174
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff8152cc68-ffffffff8152ccfe: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815879c3)
Location: drivers/acpi/acpica/utxferror.c:174
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff815879c3-ffffffff81587a59: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815beb52)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff815beb52-ffffffff815bebe5: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815d7fb9)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff815d7fb9-ffffffff815d804c: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816099d7)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff816099d7-ffffffff81609a6c: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8162ae78)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff8162ae78-ffffffff8162af0d: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d7661)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff816d7661-ffffffff816d76f6: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816f5607)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff816f5607-ffffffff816f569c: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d74a4)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff816d74a4-ffffffff816d7539: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8174f010)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff8174f010-ffffffff8174f0a5: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81881a15)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81881a15-ffffffff81881acd: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff819c64c0)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff819c64c0-ffffffff819c6580: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a0d8c0)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81a0d8c0-ffffffff81a0d980: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a588c0)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81a588c0-ffffffff81a58980: acpi_info (STB_GLOBAL)
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
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffff80001079f578)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffff80001079f578-ffff80001079f620: acpi_info (STB_GLOBAL)
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
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81601d71)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff81601d71-ffffffff81601e06: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815ed227)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff815ed227-ffffffff815ed2bc: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8161f158)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff8161f158-ffffffff8161f1ed: acpi_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_info(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81639008)
Location: drivers/acpi/acpica/utxferror.c:138
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81639008-ffffffff8163909d: acpi_info (STB_GLOBAL)
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
<b>Param removed. </b>
<code>const char *module_name</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 line_number</code>
</li>
<li>
<b>Param reordered. </b>
<code>module_name, line_number, format, (anon)</code> ➡️ <code>format, (anon)</code>
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
