# Function: <code>acpi_tb_validate_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff814a44aa)
Location: drivers/acpi/acpica/tbdata.c:273
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff814a44aa-ffffffff814a44e2: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff814f37ee)
Location: drivers/acpi/acpica/tbdata.c:273
Inline: True
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff814f37ee-ffffffff814f3826: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8151633c)
Location: drivers/acpi/acpica/tbdata.c:274
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff8151633c-ffffffff81516374: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81526ba4)
Location: drivers/acpi/acpica/tbdata.c:274
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff81526ba4-ffffffff81526bdc: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8157dce8)
Location: drivers/acpi/acpica/tbdata.c:326
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff8157dce8-ffffffff8157dd67: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815b4ec7)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff815b4ec7-ffffffff815b4f46: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815ce283)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff815ce283-ffffffff815ce302: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815ffaeb)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff815ffaeb-ffffffff815ffb6c: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81620f95)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81620f95-ffffffff81621016: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd6ec)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff816cd6ec-ffffffff816cd76d: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816eb6f2)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff816eb6f2-ffffffff816eb773: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd5d1)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff816cd5d1-ffffffff816cd653: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81744aa1)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81744aa1-ffffffff81744b23: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff818767b0)
Location: drivers/acpi/acpica/tbdata.c:308
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff818767b0-ffffffff81876841: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819b8360)
Location: drivers/acpi/acpica/tbdata.c:308
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff819b8360-ffffffff819b8405: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819ff4c0)
Location: drivers/acpi/acpica/tbdata.c:308
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff819ff4c0-ffffffff819ff565: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4a340)
Location: drivers/acpi/acpica/tbdata.c:308
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81a4a340-ffffffff81a4a3e5: acpi_tb_validate_table (STB_GLOBAL)
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
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffff800010796908)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffff800010796908-ffff800010796960: acpi_tb_validate_table (STB_GLOBAL)
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
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815fb747)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff815fb747-ffffffff815fb77f: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815e6c77)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
```
**Symbols:**

```
ffffffff815e6c77-ffffffff815e6caf: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81615275)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff81615275-ffffffff816152f6: acpi_tb_validate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_tb_validate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8162f125)
Location: drivers/acpi/acpica/tbdata.c:292
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_validate_temp_table
  - drivers/acpi/acpica/tbfind.c:acpi_tb_find_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info
```
**Symbols:**

```
ffffffff8162f125-ffffffff8162f1a6: acpi_tb_validate_table (STB_GLOBAL)
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
