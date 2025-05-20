# Function: <code>acpi_ex_convert_to_integer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff814944bf)
Location: drivers/acpi/acpica/exconvrt.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff814944bf-ffffffff81494595: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff814e3611)
Location: drivers/acpi/acpica/exconvrt.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff814e3611-ffffffff814e36f1: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81505e63)
Location: drivers/acpi/acpica/exconvrt.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff81505e63-ffffffff81505f45: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81516476)
Location: drivers/acpi/acpica/exconvrt.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff81516476-ffffffff81516564: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815615db)
Location: drivers/acpi/acpica/exconvrt.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff815615db-ffffffff815617a5: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815982e0)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff815982e0-ffffffff815984ac: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815b09e4)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff815b09e4-ffffffff815b0bb0: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815e2258)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff815e2258-ffffffff815e2424: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff816035ed)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff816035ed-ffffffff816037b9: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff816af893)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff816af893-ffffffff816afa5f: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff816cd1cf)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff816cd1cf-ffffffff816cd39b: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff816af19b)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff816af19b-ffffffff816af369: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81725f5a)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff81725f5a-ffffffff81726168: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff818566b1)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff818566b1-ffffffff818568d2: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (0)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff82091ea0-ffffffff82091ec5: acpi_ex_convert_to_integer.cold (STB_LOCAL)
ffffffff81991900-ffffffff81991b60: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (0)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff8211279e-ffffffff821127c3: acpi_ex_convert_to_integer.cold (STB_LOCAL)
ffffffff819d8410-ffffffff819d8672: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (0)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff821f04f2-ffffffff821f0517: acpi_ex_convert_to_integer.cold (STB_LOCAL)
ffffffff81a23100-ffffffff81a23362: acpi_ex_convert_to_integer (STB_GLOBAL)
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
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffff800010783ff0)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffff800010783ff0-ffff8000107840d4: acpi_ex_convert_to_integer (STB_GLOBAL)
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
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815ea326)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff815ea326-ffffffff815ea3ce: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815d5944)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff815d5944-ffffffff815d59ec: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815f78cd)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff815f78cd-ffffffff815f7a99: acpi_ex_convert_to_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_integer(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 implicit_conversion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff8161177d)
Location: drivers/acpi/acpica/exconvrt.c:38
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
```
**Symbols:**

```
ffffffff8161177d-ffffffff81611949: acpi_ex_convert_to_integer (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 implicit_conversion</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
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
