# Function: <code>acpi_tb_unload_table</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8151699b)
Location: drivers/acpi/acpica/tbdata.c:882
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff8151699b-ffffffff81516a36: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815270f1)
Location: drivers/acpi/acpica/tbdata.c:884
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff815270f1-ffffffff8152718c: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8157e981)
Location: drivers/acpi/acpica/tbdata.c:1045
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff8157e981-ffffffff8157ea8b: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815b5b4e)
Location: drivers/acpi/acpica/tbdata.c:1017
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff815b5b4e-ffffffff815b5c58: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815cef0a)
Location: drivers/acpi/acpica/tbdata.c:1017
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff815cef0a-ffffffff815cf014: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81600778)
Location: drivers/acpi/acpica/tbdata.c:1005
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff81600778-ffffffff8160088a: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81621c23)
Location: drivers/acpi/acpica/tbdata.c:1006
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff81621c23-ffffffff81621d35: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816ce244)
Location: drivers/acpi/acpica/tbdata.c:1009
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff816ce244-ffffffff816ce356: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816ec24a)
Location: drivers/acpi/acpica/tbdata.c:1009
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff816ec24a-ffffffff816ec35c: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816ce123)
Location: drivers/acpi/acpica/tbdata.c:1009
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff816ce123-ffffffff816ce235: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff817455f3)
Location: drivers/acpi/acpica/tbdata.c:1009
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff817455f3-ffffffff81745705: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff818773eb)
Location: drivers/acpi/acpica/tbdata.c:1042
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff818773eb-ffffffff8187750a: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819b8fe0)
Location: drivers/acpi/acpica/tbdata.c:1042
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff819b8fe0-ffffffff819b9160: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a00170)
Location: drivers/acpi/acpica/tbdata.c:1042
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff81a00170-ffffffff81a002f0: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4aff0)
Location: drivers/acpi/acpica/tbdata.c:1042
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff81a4aff0-ffffffff81a4b170: acpi_tb_unload_table (STB_GLOBAL)
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
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffff8000107972e0)
Location: drivers/acpi/acpica/tbdata.c:1006
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffff8000107972e0-ffff80001079738c: acpi_tb_unload_table (STB_GLOBAL)
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
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815fbf29)
Location: drivers/acpi/acpica/tbdata.c:1006
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff815fbf29-ffffffff815fbfb9: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815e7454)
Location: drivers/acpi/acpica/tbdata.c:1006
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff815e7454-ffffffff815e74e4: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81615f03)
Location: drivers/acpi/acpica/tbdata.c:1006
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff81615f03-ffffffff81616015: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_tb_unload_table(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8162fdb3)
Location: drivers/acpi/acpica/tbdata.c:1006
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff8162fdb3-ffffffff8162fec5: acpi_tb_unload_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
