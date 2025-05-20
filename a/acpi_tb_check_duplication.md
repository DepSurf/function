# Function: <code>acpi_tb_check_duplication</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8157df4d)
Location: drivers/acpi/acpica/tbdata.c:426
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
In drivers/acpi/acpica/tbdata.c (ffffffff815b512c)
Location: drivers/acpi/acpica/tbdata.c:392
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
In drivers/acpi/acpica/tbdata.c (ffffffff815ce4ec)
Location: drivers/acpi/acpica/tbdata.c:392
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
In drivers/acpi/acpica/tbdata.c (ffffffff815ffd55)
Location: drivers/acpi/acpica/tbdata.c:392
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
In drivers/acpi/acpica/tbdata.c (ffffffff816211ff)
Location: drivers/acpi/acpica/tbdata.c:392
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd56c)
Location: drivers/acpi/acpica/tbdata.c:392
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff816cd56c-ffffffff816cd669: acpi_tb_check_duplication (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816eb572)
Location: drivers/acpi/acpica/tbdata.c:392
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff816eb572-ffffffff816eb66f: acpi_tb_check_duplication (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd3ca)
Location: drivers/acpi/acpica/tbdata.c:392
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff816cd3ca-ffffffff816cd54e: acpi_tb_check_duplication (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8174489a)
Location: drivers/acpi/acpica/tbdata.c:392
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff8174489a-ffffffff81744a1e: acpi_tb_check_duplication (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8187656b)
Location: drivers/acpi/acpica/tbdata.c:420
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff8187656b-ffffffff81876715: acpi_tb_check_duplication (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819b7f50)
Location: drivers/acpi/acpica/tbdata.c:420
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff819b7f50-ffffffff819b8138: acpi_tb_check_duplication (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819ff0a0)
Location: drivers/acpi/acpica/tbdata.c:420
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff819ff0a0-ffffffff819ff287: acpi_tb_check_duplication (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_tb_check_duplication(struct acpi_table_desc *table_desc, u32 *table_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a49f20)
Location: drivers/acpi/acpica/tbdata.c:420
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff81a49f20-ffffffff81a4a107: acpi_tb_check_duplication (STB_LOCAL)
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
In drivers/acpi/acpica/tbdata.c (0)
Location: drivers/acpi/acpica/tbdata.c:392
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
In drivers/acpi/acpica/tbdata.c (0)
Location: drivers/acpi/acpica/tbdata.c:392
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
In drivers/acpi/acpica/tbdata.c (0)
Location: drivers/acpi/acpica/tbdata.c:392
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
In drivers/acpi/acpica/tbdata.c (ffffffff816154df)
Location: drivers/acpi/acpica/tbdata.c:392
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
In drivers/acpi/acpica/tbdata.c (ffffffff8162f38f)
Location: drivers/acpi/acpica/tbdata.c:392
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
