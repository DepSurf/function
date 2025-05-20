# Function: <code>acpi_ut_exit</code>

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
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81581c8a)
Location: drivers/acpi/acpica/utdebug.c:418
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff81581c8a-ffffffff81581cee: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b8e43)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff815b8e43-ffffffff815b8ea7: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d2214)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff815d2214-ffffffff815d2278: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603b05)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff81603b05-ffffffff81603b70: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81624faf)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff81624faf-ffffffff8162501a: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1749)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff816d1749-ffffffff816d17b5: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816ef727)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff816ef727-ffffffff816ef793: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d158c)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff816d158c-ffffffff816d15f8: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81748ce6)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff81748ce6-ffffffff81748d52: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187ae69)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff8187ae69-ffffffff8187af0b: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819bdcc0)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff819bdcc0-ffffffff819bdd64: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a04eb0)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff81a04eb0-ffffffff81a04f54: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a4fd50)
Location: drivers/acpi/acpica/utdebug.c:403
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff81a4fd50-ffffffff81a4fdf4: acpi_ut_exit (STB_GLOBAL)
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
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8161928f)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff8161928f-ffffffff816192fa: acpi_ut_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char *function_name, const char *module_name, u32 component_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8163313f)
Location: drivers/acpi/acpica/utdebug.c:398
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
```
**Symbols:**

```
ffffffff8163313f-ffffffff816331aa: acpi_ut_exit (STB_GLOBAL)
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
