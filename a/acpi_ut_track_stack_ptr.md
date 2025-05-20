# Function: <code>acpi_ut_track_stack_ptr</code>

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
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81581ebd)
Location: drivers/acpi/acpica/utdebug.c:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81581ebd-ffffffff81581f17: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b9072)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff815b9072-ffffffff815b90cc: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d2443)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff815d2443-ffffffff815d249d: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603d38)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81603d38-ffffffff81603d92: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816251e2)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff816251e2-ffffffff8162523c: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1982)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff816d1982-ffffffff816d19dc: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816ef960)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff816ef960-ffffffff816ef9ba: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d17c5)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff816d17c5-ffffffff816d181f: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81748f1f)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81748f1f-ffffffff81748f79: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187b16e)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff8187b16e-ffffffff8187b1ce: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819be02c)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff819be1d0-ffffffff819be230: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a0521c)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81a053c0-ffffffff81a05420: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a500bc)
Location: drivers/acpi/acpica/utdebug.c:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81a50260-ffffffff81a502c0: acpi_ut_track_stack_ptr (STB_GLOBAL)
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
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816194c2)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff816194c2-ffffffff8161951c: acpi_ut_track_stack_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81633372)
Location: drivers/acpi/acpica/utdebug.c:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed
  - drivers/acpi/acpica/nsxfname.c:acpi_get_handle
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common
  - drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length
  - drivers/acpi/acpica/rsutils.c:acpi_rs_move_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask
  - drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement
  - drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception
  - drivers/acpi/acpica/utdebug.c:acpi_trace_point
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str
  - drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push
  - drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr
  - drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length
  - drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type
  - drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource
  - drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state
  - drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list
```
**Symbols:**

```
ffffffff81633372-ffffffff816333cc: acpi_ut_track_stack_ptr (STB_GLOBAL)
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
