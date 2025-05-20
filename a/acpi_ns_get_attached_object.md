# Function: <code>acpi_ns_get_attached_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8149d71a)
Location: drivers/acpi/acpica/nsobject.c:278
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8149d71a-ffffffff8149d76a: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff814ec960)
Location: drivers/acpi/acpica/nsobject.c:278
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff814ec960-ffffffff814ec9b0: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8150f221)
Location: drivers/acpi/acpica/nsobject.c:278
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8150f221-ffffffff8150f271: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8151f8e5)
Location: drivers/acpi/acpica/nsobject.c:278
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_alias
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff8151f8e5-ffffffff8151f92c: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81572960)
Location: drivers/acpi/acpica/nsobject.c:278
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
```
**Symbols:**

```
ffffffff81572960-ffffffff81572a29: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815a98cd)
Location: drivers/acpi/acpica/nsobject.c:242
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
```
**Symbols:**

```
ffffffff815a98cd-ffffffff815a9996: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815c2775)
Location: drivers/acpi/acpica/nsobject.c:242
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
```
**Symbols:**

```
ffffffff815c2775-ffffffff815c283e: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815f4168)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
```
**Symbols:**

```
ffffffff815f4168-ffffffff815f4239: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81615607)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
```
**Symbols:**

```
ffffffff81615607-ffffffff816156d8: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816c1b28)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816c1b28-ffffffff816c1bf9: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816df690)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816df690-ffffffff816df761: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816c157b)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816c157b-ffffffff816c164c: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81738868)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81738868-ffffffff81738939: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81869c5e)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81869c5e-ffffffff81869d36: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff819a8cd0)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff819a8cd0-ffffffff819a8dcd: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff819efb80)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff819efb80-ffffffff819efc7d: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81a3a970)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81a3a970-ffffffff81a3aa6d: acpi_ns_get_attached_object (STB_GLOBAL)
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
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffff80001078df8c)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffff80001078df8c-ffff80001078e004: acpi_ns_get_attached_object (STB_GLOBAL)
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
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815f3e6d)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815f3e6d-ffffffff815f3ec0: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815df3f1)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
```
**Symbols:**

```
ffffffff815df3f1-ffffffff815df444: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816098e7)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
```
**Symbols:**

```
ffffffff816098e7-ffffffff816099b8: acpi_ns_get_attached_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_attached_object(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81623797)
Location: drivers/acpi/acpica/nsobject.c:246
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_create_node
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk
```
**Symbols:**

```
ffffffff81623797-ffffffff81623868: acpi_ns_get_attached_object (STB_GLOBAL)
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
