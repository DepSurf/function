# Function: <code>acpi_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814aa868)
Location: drivers/acpi/acpica/utxferror.c:104
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_state
```
**Symbols:**

```
ffffffff814aa868-ffffffff814aa926: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814f9abe)
Location: drivers/acpi/acpica/utxferror.c:104
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff814f9abe-ffffffff814f9b7c: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8151c641)
Location: drivers/acpi/acpica/utxferror.c:104
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8151c641-ffffffff8151c6ff: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8152ce4c)
Location: drivers/acpi/acpica/utxferror.c:104
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8152ce4c-ffffffff8152cf0a: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81587ba7)
Location: drivers/acpi/acpica/utxferror.c:104
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81587ba7-ffffffff81587c65: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815bed29)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff815bed29-ffffffff815bede2: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815d8190)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff815d8190-ffffffff815d8249: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81609bb4)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81609bb4-ffffffff81609c6f: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8162b055)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8162b055-ffffffff8162b110: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d783e)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/sysfs.c:get_status
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/ac.c:get_ac_property
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff816d783e-ffffffff816d78f9: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816f57e4)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/sysfs.c:get_status
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/ac.c:get_ac_property
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff816f57e4-ffffffff816f589f: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d7681)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816d7681-ffffffff816d773c: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8174f1ed)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8174f1ed-ffffffff8174f2a8: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81881c5b)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81881c5b-ffffffff81881d39: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff819c6750)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff819c6750-ffffffff819c683a: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a0db50)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81a0db50-ffffffff81a0dc3a: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a58b50)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81a58b50-ffffffff81a58c3a: acpi_exception (STB_GLOBAL)
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
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffff80001079f7a8)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffff80001079f7a8-ffff80001079f894: acpi_exception (STB_GLOBAL)
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
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81601f4e)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff81601f4e-ffffffff81602009: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815ed404)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff815ed404-ffffffff815ed4bf: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8161f335)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8161f335-ffffffff8161f3f0: acpi_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816391e5)
Location: drivers/acpi/acpica/utxferror.c:68
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/tbxfload.c:acpi_load_tables
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff816391e5-ffffffff816392a0: acpi_exception (STB_GLOBAL)
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
