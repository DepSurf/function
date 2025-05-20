# Function: <code>acpi_debug_print_raw</code>

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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81581d5e)
Location: drivers/acpi/acpica/utdebug.c:236
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81581d5e-ffffffff81581dcc: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b8f17)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff815b8f17-ffffffff815b8f81: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d22e8)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff815d22e8-ffffffff815d2352: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603be6)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81603be6-ffffffff81603c50: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81625090)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81625090-ffffffff816250fa: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d182c)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff816d182c-ffffffff816d189a: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816ef80a)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff816ef80a-ffffffff816ef878: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d166f)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff816d166f-ffffffff816d16dd: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81748dc9)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81748dc9-ffffffff81748e37: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187afba)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8187afba-ffffffff8187b044: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819bde50)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff819bde50-ffffffff819bdee6: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a05040)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81a05040-ffffffff81a050d6: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a4fee0)
Location: drivers/acpi/acpica/utdebug.c:221
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81a4fee0-ffffffff81a4ff76: acpi_debug_print_raw (STB_GLOBAL)
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81619370)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81619370-ffffffff816193da: acpi_debug_print_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81633220)
Location: drivers/acpi/acpica/utdebug.c:216
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81633220-ffffffff8163328a: acpi_debug_print_raw (STB_GLOBAL)
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
