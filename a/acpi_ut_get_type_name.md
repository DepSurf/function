# Function: <code>acpi_ut_get_type_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814a7109)
Location: drivers/acpi/acpica/utdecode.c:223
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
**Symbols:**

```
ffffffff814a7109-ffffffff814a712a: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814f64d8)
Location: drivers/acpi/acpica/utdecode.c:224
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff814f648c-ffffffff814f64ad: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8151909b)
Location: drivers/acpi/acpica/utdecode.c:225
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff8151904f-ffffffff81519070: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815298b1)
Location: drivers/acpi/acpica/utdecode.c:225
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff81529865-ffffffff81529886: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81582413)
Location: drivers/acpi/acpica/utdecode.c:225
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81582250-ffffffff81582271: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815b95c8)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff815b9405-ffffffff815b9426: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815d2999)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff815d27d6-ffffffff815d27f7: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8160429a)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816040d4-ffffffff816040f5: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81625744)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8162557e-ffffffff8162559f: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1d24)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816d1d24-ffffffff816d1d45: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816efd02)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816efd02-ffffffff816efd23: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1b67)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816d1b67-ffffffff816d1b88: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff817492e9)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff817492e9-ffffffff8174931e: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8187b626)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8187b626-ffffffff8187b66b: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff819be7c7)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff819be720-ffffffff819be76a: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a059b7)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81a05910-ffffffff81a0595a: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a50857)
Location: drivers/acpi/acpica/utdecode.c:192
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81a507b0-ffffffff81a507fa: acpi_ut_get_type_name (STB_GLOBAL)
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
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffff80001079b00c)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffff80001079af94-ffff80001079afd8: acpi_ut_get_type_name (STB_GLOBAL)
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
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815fe528)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815fe4dc-ffffffff815fe4fd: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815e9a1f)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815e99d3-ffffffff815e99f4: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81619a24)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8161985e-ffffffff8161987f: acpi_ut_get_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_ut_get_type_name(acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816338d4)
Location: drivers/acpi/acpica/utdecode.c:191
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8163370e-ffffffff8163372f: acpi_ut_get_type_name (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>const char *</code>
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
