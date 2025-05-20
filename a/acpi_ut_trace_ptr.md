# Function: <code>acpi_ut_trace_ptr</code>

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
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81581fb7)
Location: drivers/acpi/acpica/utdebug.c:310
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81581fb7-ffffffff8158202b: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b916c)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff815b916c-ffffffff815b91e0: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d253d)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff815d253d-ffffffff815d25b1: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603e37)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81603e37-ffffffff81603ea9: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816252e1)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816252e1-ffffffff81625353: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1a82)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_get_arguments
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_package_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816d1a82-ffffffff816d1af5: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816efa60)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_get_arguments
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_package_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816efa60-ffffffff816efad3: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d18c5)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816d18c5-ffffffff816d1938: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8174901f)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff8174901f-ffffffff81749092: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187b290)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff8187b290-ffffffff8187b317: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819be240)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff819be240-ffffffff819be2f5: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a05430)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81a05430-ffffffff81a054e5: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a502d0)
Location: drivers/acpi/acpica/utdebug.c:295
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81a502d0-ffffffff81a50385: acpi_ut_trace_ptr (STB_GLOBAL)
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
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816195c1)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff816195c1-ffffffff81619633: acpi_ut_trace_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const void *pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81633471)
Location: drivers/acpi/acpica/utdebug.c:290
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_push_scope
  - drivers/acpi/acpica/psscope.c:acpi_ps_init_scope
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
```
**Symbols:**

```
ffffffff81633471-ffffffff816334e3: acpi_ut_trace_ptr (STB_GLOBAL)
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
