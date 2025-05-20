# Function: <code>acpi_ps_get_opcode_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff814a1b6d)
Location: drivers/acpi/acpica/psopinfo.c:161
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
```
**Symbols:**

```
ffffffff814a1b6d-ffffffff814a1b7f: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff814f0e86)
Location: drivers/acpi/acpica/psopinfo.c:161
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
```
**Symbols:**

```
ffffffff814f0e86-ffffffff814f0e98: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815138db)
Location: drivers/acpi/acpica/psopinfo.c:161
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
```
**Symbols:**

```
ffffffff815138db-ffffffff815138ed: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8152403c)
Location: drivers/acpi/acpica/psopinfo.c:161
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
```
**Symbols:**

```
ffffffff8152403c-ffffffff8152404e: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8157974e)
Location: drivers/acpi/acpica/psopinfo.c:161
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff8157974e-ffffffff81579764: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815b084c)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
```
**Symbols:**

```
ffffffff815b084c-ffffffff815b0862: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815c98f0)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815c98f0-ffffffff815c9906: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815fb089)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815fb089-ffffffff815fb09f: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8161c530)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8161c530-ffffffff8161c546: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff816c8ab9)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816c8ab9-ffffffff816c8acf: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff816e6adf)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816e6adf-ffffffff816e6af5: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff816c89a0)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816c89a0-ffffffff816c89b6: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8173fd2e)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8173fd2e-ffffffff8173fd44: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff818715fd)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff818715fd-ffffffff81871619: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff819b1fa0)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff819b1fa0-ffffffff819b207e: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff819f8e90)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff819f8e90-ffffffff819f8f70: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff81a43ce0)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81a43ce0-ffffffff81a43dc0: acpi_ps_get_opcode_name (STB_GLOBAL)
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
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffff8000107932cc)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffff8000107932cc-ffff8000107932ec: acpi_ps_get_opcode_name (STB_GLOBAL)
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
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815f8892)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff815f8892-ffffffff815f88a4: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff815e3dd1)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
**Symbols:**

```
ffffffff815e3dd1-ffffffff815e3de3: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff81610810)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81610810-ffffffff81610826: acpi_ps_get_opcode_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *acpi_ps_get_opcode_name(u16 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psopinfo.c (ffffffff8162a6c0)
Location: drivers/acpi/acpica/psopinfo.c:127
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8162a6c0-ffffffff8162a6d6: acpi_ps_get_opcode_name (STB_GLOBAL)
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
