# Function: <code>acpi_tb_compare_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff814a552d)
Location: drivers/acpi/acpica/tbinstal.c:70
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff814f4890)
Location: drivers/acpi/acpica/tbinstal.c:70
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff815174d4)
Location: drivers/acpi/acpica/tbinstal.c:70
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
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
In drivers/acpi/acpica/tbinstal.c (ffffffff81527cfe)
Location: drivers/acpi/acpica/tbinstal.c:70
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff8157df95)
Location: drivers/acpi/acpica/tbdata.c:75
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff815b5174)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff815ce530)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff815ffd9a)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff81621244)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 acpi_tb_compare_tables(struct acpi_table_desc *table_desc, u32 table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd4c5)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
```
**Symbols:**

```
ffffffff816cd4c5-ffffffff816cd56c: acpi_tb_compare_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 acpi_tb_compare_tables(struct acpi_table_desc *table_desc, u32 table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816eb4cb)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
```
**Symbols:**

```
ffffffff816eb4cb-ffffffff816eb572: acpi_tb_compare_tables (STB_LOCAL)
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
In drivers/acpi/acpica/tbdata.c (ffffffff816cd43b)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
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
In drivers/acpi/acpica/tbdata.c (ffffffff8174490b)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff818765dc)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819b7fb1)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819ff100)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a49f80)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
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
In drivers/acpi/acpica/tbdata.c (ffff800010796b70)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff815fb900)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff815e6e30)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff81615524)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
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
In drivers/acpi/acpica/tbdata.c (ffffffff8162f3d4)
Location: drivers/acpi/acpica/tbdata.c:41
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
