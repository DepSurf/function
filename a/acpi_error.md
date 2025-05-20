# Function: <code>acpi_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814aa53e)
Location: drivers/acpi/acpica/utxferror.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_init_generic_address
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_fixed_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_fixed_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
**Symbols:**

```
ffffffff814aa53e-ffffffff814aa5e5: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814f978c)
Location: drivers/acpi/acpica/utxferror.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_init_generic_address
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_fixed_table
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_fixed_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
**Symbols:**

```
ffffffff814f978c-ffffffff814f9833: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8151c30f)
Location: drivers/acpi/acpica/utxferror.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
**Symbols:**

```
ffffffff8151c30f-ffffffff8151c3b6: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8152cb1a)
Location: drivers/acpi/acpica/utxferror.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
**Symbols:**

```
ffffffff8152cb1a-ffffffff8152cbc1: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81587875)
Location: drivers/acpi/acpica/utxferror.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method
```
**Symbols:**

```
ffffffff81587875-ffffffff8158791c: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815bea0e)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method
```
**Symbols:**

```
ffffffff815bea0e-ffffffff815beab0: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815d7e75)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff815d7e75-ffffffff815d7f17: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8160988f)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff8160988f-ffffffff81609933: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8162ad30)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff8162ad30-ffffffff8162add4: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d7519)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_init_generic_address
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff816d7519-ffffffff816d75bd: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816f54bf)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_init_generic_address
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff816f54bf-ffffffff816f5563: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d735c)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_init_generic_address
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff816d735c-ffffffff816d7400: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8174eec8)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_init_generic_address
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff8174eec8-ffffffff8174ef6c: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81881887)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81881887-ffffffff8188194e: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff819c6300)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff819c6300-ffffffff819c63d0: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a0d700)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81a0d700-ffffffff81a0d7d0: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a58700)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81a58700-ffffffff81a587d0: acpi_error (STB_GLOBAL)
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
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffff80001079f3f0)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
**Symbols:**

```
ffff80001079f3f0-ffff80001079f4b4: acpi_error (STB_GLOBAL)
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
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81601c29)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
**Symbols:**

```
ffffffff81601c29-ffffffff81601ccd: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815ed0df)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
**Symbols:**

```
ffffffff815ed0df-ffffffff815ed183: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8161f010)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff8161f010-ffffffff8161f0b4: acpi_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81638ec0)
Location: drivers/acpi/acpica/utxferror.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_push
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exfield.c:acpi_ex_get_protocol_buffer_length
  - drivers/acpi/acpica/exfldio.c:acpi_ex_extract_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_numeric_op
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_read
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_request
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_pathname_length
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_resource_to_aml
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utmath.c:acpi_ut_divide
  - drivers/acpi/acpica/utmath.c:acpi_ut_short_divide
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff81638ec0-ffffffff81638f64: acpi_error (STB_GLOBAL)
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
