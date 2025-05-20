# Function: <code>acpi_hw_gpe_read</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_read(u64 *value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816d8ca8)
Location: drivers/acpi/acpica/hwgpe.c:43
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff816d8ca8-ffffffff816d8d74: acpi_hw_gpe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_read(u64 *value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816bac40)
Location: drivers/acpi/acpica/hwgpe.c:43
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff816bac40-ffffffff816bad0c: acpi_hw_gpe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_read(u64 *value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81731c87)
Location: drivers/acpi/acpica/hwgpe.c:43
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81731c87-ffffffff81731d53: acpi_hw_gpe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_gpe_read(u64 *value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff818629d5)
Location: drivers/acpi/acpica/hwgpe.c:43
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff818629d5-ffffffff81862ab9: acpi_hw_gpe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_hw_gpe_read(u64 *value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff819a0230)
Location: drivers/acpi/acpica/hwgpe.c:43
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff819a0230-ffffffff819a0317: acpi_hw_gpe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_hw_gpe_read(u64 *value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff819e6f00)
Location: drivers/acpi/acpica/hwgpe.c:43
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff819e6f00-ffffffff819e6fe7: acpi_hw_gpe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_hw_gpe_read(u64 *value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81a31c50)
Location: drivers/acpi/acpica/hwgpe.c:43
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81a31c50-ffffffff81a31d37: acpi_hw_gpe_read (STB_GLOBAL)
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
