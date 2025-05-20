# Function: <code>acpi_hw_validate_io_block</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_block(u64 address, u32 bit_width, u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff816da71f)
Location: drivers/acpi/acpica/hwvalid.c:310
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
**Symbols:**

```
ffffffff816da71f-ffffffff816da7b3: acpi_hw_validate_io_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_block(u64 address, u32 bit_width, u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff816bc6bc)
Location: drivers/acpi/acpica/hwvalid.c:310
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
**Symbols:**

```
ffffffff816bc6bc-ffffffff816bc750: acpi_hw_validate_io_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_block(u64 address, u32 bit_width, u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff817338dd)
Location: drivers/acpi/acpica/hwvalid.c:310
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
**Symbols:**

```
ffffffff817338dd-ffffffff81733971: acpi_hw_validate_io_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_block(u64 address, u32 bit_width, u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff8186480e)
Location: drivers/acpi/acpica/hwvalid.c:310
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
**Symbols:**

```
ffffffff8186480e-ffffffff818648ad: acpi_hw_validate_io_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_block(u64 address, u32 bit_width, u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff819a2700)
Location: drivers/acpi/acpica/hwvalid.c:311
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
**Symbols:**

```
ffffffff819a2700-ffffffff819a27c3: acpi_hw_validate_io_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_block(u64 address, u32 bit_width, u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff819e93b0)
Location: drivers/acpi/acpica/hwvalid.c:311
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
**Symbols:**

```
ffffffff819e93b0-ffffffff819e9473: acpi_hw_validate_io_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_block(u64 address, u32 bit_width, u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff81a34100)
Location: drivers/acpi/acpica/hwvalid.c:311
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
**Symbols:**

```
ffffffff81a34100-ffffffff81a341c3: acpi_hw_validate_io_block (STB_GLOBAL)
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
