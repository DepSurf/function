# Function: <code>get_unaligned_be24</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_trace.c (ffffffff8183f44b)
Location: include/linux/unaligned/generic.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_trace.c (ffffffff8184faab)
Location: include/linux/unaligned/generic.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
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
In drivers/scsi/scsi_trace.c (ffffffff81832d76)
Location: include/linux/unaligned/generic.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
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
In drivers/scsi/scsi_trace.c (ffffffff818bedc6)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
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
In drivers/scsi/scsi_trace.c (ffffffff81a0b237)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b17c55)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_24_be
```
```
In drivers/scsi/scsi_trace.c (ffffffff81b8ac67)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/firmware/dmi_scan.c (ffffffff83f04e54)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b66a75)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_24_be
```
```
In drivers/scsi/scsi_trace.c (ffffffff81bdebd9)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/firmware/dmi_scan.c (ffffffff8372ae04)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bba8f5)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_24_be
```
```
In drivers/scsi/scsi_trace.c (ffffffff81c33ac9)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/firmware/dmi_scan.c (ffffffff8395edc4)
Location: include/asm-generic/unaligned.h:90
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
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
