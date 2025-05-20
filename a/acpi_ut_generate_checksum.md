# Function: <code>acpi_ut_generate_checksum</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_generate_checksum(void *table, u32 length, u8 original_checksum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utcksum.c (ffffffff819bca96)
Location: drivers/acpi/acpica/utcksum.c:129
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcksum.c:acpi_ut_verify_cdat_checksum
  - drivers/acpi/acpica/utcksum.c:acpi_ut_verify_checksum
```
**Symbols:**

```
ffffffff819bcb10-ffffffff819bcb43: acpi_ut_generate_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_generate_checksum(void *table, u32 length, u8 original_checksum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utcksum.c (ffffffff81a03c36)
Location: drivers/acpi/acpica/utcksum.c:129
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcksum.c:acpi_ut_verify_cdat_checksum
  - drivers/acpi/acpica/utcksum.c:acpi_ut_verify_checksum
```
**Symbols:**

```
ffffffff81a03cb0-ffffffff81a03ce3: acpi_ut_generate_checksum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 acpi_ut_generate_checksum(void *table, u32 length, u8 original_checksum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utcksum.c (ffffffff81a4ead6)
Location: drivers/acpi/acpica/utcksum.c:129
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcksum.c:acpi_ut_verify_cdat_checksum
  - drivers/acpi/acpica/utcksum.c:acpi_ut_verify_checksum
```
**Symbols:**

```
ffffffff81a4eb50-ffffffff81a4eb83: acpi_ut_generate_checksum (STB_GLOBAL)
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
