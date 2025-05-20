# Function: <code>acpi_ex_dump_operand</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff81562efe)
Location: drivers/acpi/acpica/exdump.c:615
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81562efe-ffffffff815633ba: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff81599c08)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81599c08-ffffffff8159a0c4: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff815b2382)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815b2382-ffffffff815b28c0: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff815e3cb3)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815e3d07-ffffffff815e4278: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff815e3cb3-ffffffff815e3d07: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff81605048)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8160509c-ffffffff8160560d: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff81605048-ffffffff8160509c: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff816b12e3)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816b1337-ffffffff816b18a4: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff816b12e3-ffffffff816b1337: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff816cec1f)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816cec73-ffffffff816cf1e0: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff816cec1f-ffffffff816cec73: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff816b0be0)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816b0c34-ffffffff816b119b: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff816b0be0-ffffffff816b0c34: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff81727a02)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81727a56-ffffffff81727fbd: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff81727a02-ffffffff81727a56: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff818581c0)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81858238-ffffffff81858761: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff818581c0-ffffffff81858238: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff819940f2)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81993aa0-ffffffff81994065: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff81993a00-ffffffff81993a8a: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff819daca2)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff819da650-ffffffff819dac17: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff819da5b0-ffffffff819da63a: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff81a25992)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81a25340-ffffffff81a25907: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff81a252a0-ffffffff81a2532a: acpi_ex_dump_operand (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff815f9328)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815f937c-ffffffff815f98ed: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff815f9328-ffffffff815f937c: acpi_ex_dump_operand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ex_dump_operand(union acpi_operand_object *obj_desc, u32 depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exdump.c (ffffffff816131d8)
Location: drivers/acpi/acpica/exdump.c:581
Inline: True
Direct callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8161322c-ffffffff8161379d: acpi_ex_dump_operand.part.0 (STB_LOCAL)
ffffffff816131d8-ffffffff8161322c: acpi_ex_dump_operand (STB_GLOBAL)
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
