# Function: <code>acpi_ut_acquire_mutex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff814a8bf3)
Location: drivers/acpi/acpica/utmutex.c:240
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exdebug.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/exdebug.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/exdebug.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff814a8bf3-ffffffff814a8c79: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff814f7ec4)
Location: drivers/acpi/acpica/utmutex.c:223
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff814f7ec4-ffffffff814f7f44: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff8151aae0)
Location: drivers/acpi/acpica/utmutex.c:223
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_put_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff8151aae0-ffffffff8151ab60: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff8152b303)
Location: drivers/acpi/acpica/utmutex.c:223
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_put_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff8152b303-ffffffff8152b384: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff81584ecd)
Location: drivers/acpi/acpica/utmutex.c:223
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff81584ecd-ffffffff8158508d: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff815bc03f)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff815bc03f-ffffffff815bc20a: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff815d5485)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff815d5485-ffffffff815d5650: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff81606e1b)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff81606e1b-ffffffff81606fe3: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff816282b6)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff816282b6-ffffffff8162847e: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff816d4a50)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff816d4a50-ffffffff816d4c18: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff816f2a1d)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff816f2a1d-ffffffff816f2be5: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff816d48ce)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff816d48ce-ffffffff816d4a96: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff8174c244)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff8174c244-ffffffff8174c46e: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff8187e8a7)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfobj.c:acpi_get_type
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff8187e8a7-ffffffff8187eadf: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff819c25d0)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_execute_reg_methods
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_internal
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_data
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfobj.c:acpi_get_type
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff819c25d0-ffffffff819c2833: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff81a09920)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_execute_reg_methods
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_internal
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_data
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfobj.c:acpi_get_type
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff81a09920-ffffffff81a09b83: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff81a548c0)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/evxfregn.c:acpi_execute_reg_methods
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_internal
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_data
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfobj.c:acpi_get_type
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_install_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff81a548c0-ffffffff81a54b23: acpi_ut_acquire_mutex (STB_GLOBAL)
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
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffff80001079d07c)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffff80001079d07c-ffff80001079d134: acpi_ut_acquire_mutex (STB_GLOBAL)
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
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff81600092)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff81600092-ffffffff81600126: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff815eb57a)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff815eb57a-ffffffff815eb60e: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff8161c596)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff8161c596-ffffffff8161c75e: acpi_ut_acquire_mutex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ut_acquire_mutex(acpi_mutex_handle mutex_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utmutex.c (ffffffff81636446)
Location: drivers/acpi/acpica/utmutex.c:187
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/psxface.c:acpi_debug_trace
  - drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag
  - drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded
  - drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
```
**Symbols:**

```
ffffffff81636446-ffffffff8163660e: acpi_ut_acquire_mutex (STB_GLOBAL)
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
