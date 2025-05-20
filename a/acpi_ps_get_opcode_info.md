# Function: <code>acpi_ps_get_opcode_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff814a1b24)
Location: drivers/acpi/acpica/psopinfo.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff814a1b24-ffffffff814a1b6d: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff814f0e3d)
Location: drivers/acpi/acpica/psopinfo.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff814f0e3d-ffffffff814f0e86: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff81513892)
Location: drivers/acpi/acpica/psopinfo.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff81513892-ffffffff815138db: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff81523ff3)
Location: drivers/acpi/acpica/psopinfo.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff81523ff3-ffffffff8152403c: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815796b6)
Location: drivers/acpi/acpica/psopinfo.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff815796b6-ffffffff8157974e: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815b07b4)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff815b07b4-ffffffff815b084c: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815c9858)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff815c9858-ffffffff815c98f0: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815fafee)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff815fafee-ffffffff815fb089: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8161c495)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff8161c495-ffffffff8161c530: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff816c8a1e)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff816c8a1e-ffffffff816c8ab9: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff816e6a44)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff816e6a44-ffffffff816e6adf: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff816c8905)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff816c8905-ffffffff816c89a0: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8173fc70)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff8173fc70-ffffffff8173fd2e: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff81871529)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff81871529-ffffffff818715fd: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff819b1fa9)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: True
Inline callers:
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff819b1e90-ffffffff819b1f81: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff819f8e95)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: True
Inline callers:
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff819f8da0-ffffffff819f8e7d: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff81a43ce5)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: True
Inline callers:
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff81a43bf0-ffffffff81a43ccd: acpi_ps_get_opcode_info (STB_GLOBAL)
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
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffff800010793254)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffff800010793254-ffff8000107932cc: acpi_ps_get_opcode_info (STB_GLOBAL)
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
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815f8849)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff815f8849-ffffffff815f8892: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815e3d88)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
**Symbols:**

```
ffffffff815e3d88-ffffffff815e3dd1: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff81610775)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff81610775-ffffffff81610810: acpi_ps_get_opcode_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct acpi_opcode_info *acpi_ps_get_opcode_info(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8162a625)
Location: drivers/acpi/acpica/psopinfo.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/pstree.c:acpi_ps_append_arg
  - drivers/acpi/acpica/pstree.c:acpi_ps_get_arg
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_init_op
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
```
**Symbols:**

```
ffffffff8162a625-ffffffff8162a6c0: acpi_ps_get_opcode_info (STB_GLOBAL)
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
