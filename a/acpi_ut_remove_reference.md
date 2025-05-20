# Function: <code>acpi_ut_remove_reference</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff814a723f)
Location: drivers/acpi/acpica/utdelete.c:727
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_SUB
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff814a723f-ffffffff814a7270: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff814f65c2)
Location: drivers/acpi/acpica/utdelete.c:728
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff814f65c2-ffffffff814f65f3: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81519185)
Location: drivers/acpi/acpica/utdelete.c:728
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81519185-ffffffff815191b6: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8152999b)
Location: drivers/acpi/acpica/utdelete.c:730
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8152999b-ffffffff815299cd: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8158257e)
Location: drivers/acpi/acpica/utdelete.c:730
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff8158257e-ffffffff815825f7: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815b9733)
Location: drivers/acpi/acpica/utdelete.c:697
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff815b9733-ffffffff815b97af: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815d2b04)
Location: drivers/acpi/acpica/utdelete.c:700
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff815d2b04-ffffffff815d2b80: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81604405)
Location: drivers/acpi/acpica/utdelete.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81604405-ffffffff81604489: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816258af)
Location: drivers/acpi/acpica/utdelete.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816258af-ffffffff81625933: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816d204d)
Location: drivers/acpi/acpica/utdelete.c:701
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_epackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816d204d-ffffffff816d20d1: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816f002b)
Location: drivers/acpi/acpica/utdelete.c:701
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_epackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816f002b-ffffffff816f00af: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816d1e90)
Location: drivers/acpi/acpica/utdelete.c:709
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816d1e90-ffffffff816d1f14: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff817496cf)
Location: drivers/acpi/acpica/utdelete.c:710
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff817496cf-ffffffff81749753: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8187ba8a)
Location: drivers/acpi/acpica/utdelete.c:710
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff8187ba8a-ffffffff8187bb36: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff819bfb12)
Location: drivers/acpi/acpica/utdelete.c:710
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff819bed70-ffffffff819bee1c: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81a06d12)
Location: drivers/acpi/acpica/utdelete.c:710
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81a05f60-ffffffff81a0600c: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81a51bb2)
Location: drivers/acpi/acpica/utdelete.c:710
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81a50e00-ffffffff81a50eac: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffff80001079b22c)
Location: drivers/acpi/acpica/utdelete.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffff80001079b22c-ffff80001079b27c: acpi_ut_remove_reference (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815fe637)
Location: drivers/acpi/acpica/utdelete.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff815fe637-ffffffff815fe66a: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815e9b2e)
Location: drivers/acpi/acpica/utdelete.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff815e9b2e-ffffffff815e9b61: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81619b8f)
Location: drivers/acpi/acpica/utdelete.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81619b8f-ffffffff81619c13: acpi_ut_remove_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_remove_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81633a3f)
Location: drivers/acpi/acpica/utdelete.c:704
Inline: True
Direct callers:
  - drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_data_object_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path
  - drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands
  - drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_pop_and_delete
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81633a3f-ffffffff81633ac3: acpi_ut_remove_reference (STB_GLOBAL)
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
