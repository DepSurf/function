# Function: <code>acpi_ex_convert_to_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81494629)
Location: drivers/acpi/acpica/exconvrt.c:399
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81494629-ffffffff814947ad: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff814e3785)
Location: drivers/acpi/acpica/exconvrt.c:400
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff814e3785-ffffffff814e390a: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81505fd9)
Location: drivers/acpi/acpica/exconvrt.c:400
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81505fd9-ffffffff8150615e: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815165f8)
Location: drivers/acpi/acpica/exconvrt.c:400
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff815165f8-ffffffff8151677c: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81561905)
Location: drivers/acpi/acpica/exconvrt.c:406
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81561905-ffffffff81561b82: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff8159860c)
Location: drivers/acpi/acpica/exconvrt.c:372
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff8159860c-ffffffff81598889: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815b0d10)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff815b0d10-ffffffff815b0fa6: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815e2584)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff815e2584-ffffffff815e2819: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81603919)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81603919-ffffffff81603bae: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff816afbbf)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff816afbbf-ffffffff816afe54: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff816cd4fb)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff816cd4fb-ffffffff816cd790: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff816af4c9)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff816af4c9-ffffffff816af75e: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff817262c8)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff817262c8-ffffffff8172655d: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81856a41)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81856a41-ffffffff81856ce5: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81991d90)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81991d90-ffffffff819920c2: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff819d88a0)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff819d88a0-ffffffff819d8bcd: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81a23590)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81a23590-ffffffff81a238bd: acpi_ex_convert_to_string (STB_GLOBAL)
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
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffff800010784198)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffff800010784198-ffff800010784374: acpi_ex_convert_to_string (STB_GLOBAL)
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
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815ea464)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff815ea464-ffffffff815ea607: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815d5a82)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff815d5a82-ffffffff815d5c25: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff815f7bf9)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff815f7bf9-ffffffff815f7e8e: acpi_ex_convert_to_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ex_convert_to_string(union acpi_operand_object *obj_desc, union acpi_operand_object **result_desc, u32 type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconvrt.c (ffffffff81611aa9)
Location: drivers/acpi/acpica/exconvrt.c:373
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type
  - drivers/acpi/acpica/exmisc.c:acpi_ex_do_logical_op
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_string
```
**Symbols:**

```
ffffffff81611aa9-ffffffff81611d3e: acpi_ex_convert_to_string (STB_GLOBAL)
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
