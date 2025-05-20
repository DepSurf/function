# Function: <code>acpi_ut_add_reference</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff814a7741)
Location: drivers/acpi/acpica/utdelete.c:694
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff814a7741-ffffffff814a7764: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff814f6ac1)
Location: drivers/acpi/acpica/utdelete.c:695
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff814f6ac1-ffffffff814f6ae4: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81519684)
Location: drivers/acpi/acpica/utdelete.c:695
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff81519684-ffffffff815196a7: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81529eb4)
Location: drivers/acpi/acpica/utdelete.c:697
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff81529eb4-ffffffff81529ed7: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81582f1d)
Location: drivers/acpi/acpica/utdelete.c:697
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff81582f1d-ffffffff81582f87: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815ba0db)
Location: drivers/acpi/acpica/utdelete.c:664
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff815ba0db-ffffffff815ba145: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815d3535)
Location: drivers/acpi/acpica/utdelete.c:667
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff815d3535-ffffffff815d359f: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81604eb4)
Location: drivers/acpi/acpica/utdelete.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff81604eb4-ffffffff81604f22: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8162635e)
Location: drivers/acpi/acpica/utdelete.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff8162635e-ffffffff816263cc: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816d2b0e)
Location: drivers/acpi/acpica/utdelete.c:668
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff816d2b0e-ffffffff816d2b7c: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816f0aec)
Location: drivers/acpi/acpica/utdelete.c:668
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff816f0aec-ffffffff816f0b5a: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816d2996)
Location: drivers/acpi/acpica/utdelete.c:676
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff816d2996-ffffffff816d2a04: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8174a1da)
Location: drivers/acpi/acpica/utdelete.c:677
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff8174a1da-ffffffff8174a248: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8187c5d2)
Location: drivers/acpi/acpica/utdelete.c:677
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff8187c5d2-ffffffff8187c650: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff819bfa60)
Location: drivers/acpi/acpica/utdelete.c:677
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff819bfa60-ffffffff819bfae0: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81a06c60)
Location: drivers/acpi/acpica/utdelete.c:677
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff81a06c60-ffffffff81a06ce0: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81a51b00)
Location: drivers/acpi/acpica/utdelete.c:677
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff81a51b00-ffffffff81a51b80: acpi_ut_add_reference (STB_GLOBAL)
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
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffff80001079b7a4)
Location: drivers/acpi/acpica/utdelete.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffff80001079b7a4-ffff80001079b7e4: acpi_ut_add_reference (STB_GLOBAL)
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
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815fec0a)
Location: drivers/acpi/acpica/utdelete.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff815fec0a-ffffffff815fec2e: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815ea101)
Location: drivers/acpi/acpica/utdelete.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff815ea101-ffffffff815ea125: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8161a63e)
Location: drivers/acpi/acpica/utdelete.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff8161a63e-ffffffff8161a6ac: acpi_ut_add_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816344ee)
Location: drivers/acpi/acpica/utdelete.c:671
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
**Symbols:**

```
ffffffff816344ee-ffffffff8163455c: acpi_ut_add_reference (STB_GLOBAL)
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
