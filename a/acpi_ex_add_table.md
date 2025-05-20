# Function: <code>acpi_ex_add_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, struct acpi_namespace_node *parent_node, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81493e01)
Location: drivers/acpi/acpica/exconfig.c:82
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff81493e01-ffffffff81493ed5: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, struct acpi_namespace_node *parent_node, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff814e2f5e)
Location: drivers/acpi/acpica/exconfig.c:82
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff814e2f5e-ffffffff814e303c: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81505868)
Location: drivers/acpi/acpica/exconfig.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81505868-ffffffff815058b8: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81515e73)
Location: drivers/acpi/acpica/exconfig.c:80
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81515e73-ffffffff81515ec3: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81560bba)
Location: drivers/acpi/acpica/exconfig.c:80
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81560bba-ffffffff81560c69: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81597865)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81597865-ffffffff81597914: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff815aff69)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff815aff69-ffffffff815b0018: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff815e17f0)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff815e17f0-ffffffff815e189f: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81602b85)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81602b85-ffffffff81602c34: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff816aed74)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff816aed74-ffffffff816aee23: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff816cc6c1)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff816cc6c1-ffffffff816cc770: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff816ae68d)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff816ae68d-ffffffff816ae73c: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff8172544c)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff8172544c-ffffffff817254fb: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81855b21)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81855b21-ffffffff81855bdf: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81990bb0)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81990bb0-ffffffff81990c80: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff819d76b0)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff819d76b0-ffffffff819d7780: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81a22370)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81a22370-ffffffff81a22440: acpi_ex_add_table (STB_LOCAL)
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
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffff8000107838fc)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffff8000107838fc-ffff800010783968: acpi_ex_add_table (STB_LOCAL)
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
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff815e9cd5)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff815e9cd5-ffffffff815e9d27: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff815d52f8)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff815d52f8-ffffffff815d534a: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff815f6e65)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff815f6e65-ffffffff815f6f14: acpi_ex_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_add_table(u32 table_index, union acpi_operand_object **ddb_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffffffff81610d15)
Location: drivers/acpi/acpica/exconfig.c:46
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
```
**Symbols:**

```
ffffffff81610d15-ffffffff81610dc4: acpi_ex_add_table (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct acpi_namespace_node *parent_node</code>
</li>
<li>
<b>Param reordered. </b>
<code>table_index, parent_node, ddb_handle</code> ➡️ <code>table_index, ddb_handle</code>
</li>
</ul>
</details>
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
