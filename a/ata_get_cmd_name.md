# Function: <code>ata_get_cmd_name</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *ata_get_cmd_name(u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81ed813c)
Location: drivers/ata/libata-eh.c:2090
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_report
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81a30780-ffffffff81a30856: ata_get_cmd_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *ata_get_cmd_name(u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb4aff)
Location: drivers/ata/libata-eh.c:2096
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_report
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81bb3de0-ffffffff81bb3eb6: ata_get_cmd_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *ata_get_cmd_name(u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0bfe3)
Location: drivers/ata/libata-eh.c:2206
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_report
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81c0b300-ffffffff81c0b3d6: ata_get_cmd_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *ata_get_cmd_name(u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c611b6)
Location: drivers/ata/libata-eh.c:2213
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_report
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81c60380-ffffffff81c60456: ata_get_cmd_name (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
