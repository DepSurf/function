# Function: <code>acpi_ut_verify_checksum</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ut_verify_checksum(struct acpi_table_header *table, u32 length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utcksum.c (ffffffff819bc9d0)
Location: drivers/acpi/acpica/utcksum.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
```
**Symbols:**

```
ffffffff819bc9d0-ffffffff819bca67: acpi_ut_verify_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ut_verify_checksum(struct acpi_table_header *table, u32 length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utcksum.c (ffffffff81a03b70)
Location: drivers/acpi/acpica/utcksum.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
```
**Symbols:**

```
ffffffff81a03b70-ffffffff81a03c07: acpi_ut_verify_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ut_verify_checksum(struct acpi_table_header *table, u32 length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utcksum.c (ffffffff81a4ea10)
Location: drivers/acpi/acpica/utcksum.c:35
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
```
**Symbols:**

```
ffffffff81a4ea10-ffffffff81a4eaa7: acpi_ut_verify_checksum (STB_GLOBAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
