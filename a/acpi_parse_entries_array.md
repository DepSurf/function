# Function: <code>acpi_parse_entries_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81fa077f)
Location: drivers/acpi/tables.c:232
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_parse_entries
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
**Symbols:**

```
ffffffff81fa077f-ffffffff81fa08ae: acpi_parse_entries_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81fcc088)
Location: drivers/acpi/tables.c:241
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/tables.c:acpi_parse_entries
```
**Symbols:**

```
ffffffff81fcc088-ffffffff81fcc1b0: acpi_parse_entries_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff8200907d)
Location: drivers/acpi/tables.c:240
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
  - drivers/acpi/tables.c:acpi_parse_entries
```
**Symbols:**

```
ffffffff8200907d-ffffffff820091ca: acpi_parse_entries_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff820ea8ba)
Location: drivers/acpi/tables.c:240
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff826f381a)
Location: drivers/acpi/tables.c:240
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff8271d7eb)
Location: drivers/acpi/tables.c:245
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828d5816)
Location: drivers/acpi/tables.c:244
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828ef5f0)
Location: drivers/acpi/tables.c:283
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f8780)
Location: drivers/acpi/tables.c:284
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82d0f85a)
Location: drivers/acpi/tables.c:284
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
**Symbols:**

```
ffffffff82d0f85a-ffffffff82d0fa2f: acpi_parse_entries_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82ffd2db)
Location: drivers/acpi/tables.c:284
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
**Symbols:**

```
ffffffff82ffd2db-ffffffff82ffd46f: acpi_parse_entries_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832080cd)
Location: drivers/acpi/tables.c:284
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832f0190)
Location: drivers/acpi/tables.c:294
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:319
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
**Symbols:**

```
ffffffff81822340-ffffffff818225ff: acpi_parse_entries_array (STB_LOCAL)
ffffffff81eb61d3-ffffffff81eb620e: acpi_parse_entries_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81953120)
Location: drivers/acpi/tables.c:329
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
**Symbols:**

```
ffffffff81953120-ffffffff81953424: acpi_parse_entries_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, struct acpi_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81999520)
Location: drivers/acpi/tables.c:339
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
**Symbols:**

```
ffffffff81999520-ffffffff819997db: acpi_parse_entries_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_parse_entries_array(char *id, long unsigned int table_size, union fw_table_header *table_header, struct acpi_subtable_proc *proc, int proc_num, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fw_table.c (ffffffff8192f370)
Location: lib/fw_table.c:149
Inline: False
Direct callers:
  - lib/fw_table.c:cdat_table_parse
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
**Symbols:**

```
ffffffff8192f370-ffffffff8192f653: acpi_parse_entries_array (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffff80001147b808)
Location: drivers/acpi/tables.c:284
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828e14ec)
Location: drivers/acpi/tables.c:284
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828d9977)
Location: drivers/acpi/tables.c:284
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f437c)
Location: drivers/acpi/tables.c:284
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f97d4)
Location: drivers/acpi/tables.c:284
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_entries_array
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_table_header *table_header</code> ➡️ <code>union fw_table_header *table_header</code>
</li>
</ul>
</details>
</li>
</ul>
