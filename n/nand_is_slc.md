# Function: <code>nand_is_slc</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mtd/nand/raw/nand_base.c (c0aa1a0c)
Location: include/linux/mtd/rawnand.h:1272
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
  - drivers/mtd/nand/raw/nand_base.c:nand_detect
```
```
In drivers/mtd/nand/raw/nand_amd.c (c0aa6aac)
Location: include/linux/mtd/rawnand.h:1272
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_amd.c:amd_nand_init
```
```
In drivers/mtd/nand/raw/nand_esmt.c (c0aa6b84)
Location: include/linux/mtd/rawnand.h:1272
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_esmt.c:esmt_nand_init
```
```
In drivers/mtd/nand/raw/nand_hynix.c (c0aa76c4)
Location: include/linux/mtd/rawnand.h:1272
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_hynix.c:hynix_nand_init
```
```
In drivers/mtd/nand/raw/nand_macronix.c (c0aa7a18)
Location: include/linux/mtd/rawnand.h:1272
Inline: True
```
```
In drivers/mtd/nand/raw/nand_samsung.c (c0aa84b4)
Location: include/linux/mtd/rawnand.h:1272
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_samsung.c:samsung_nand_init
  - drivers/mtd/nand/raw/nand_samsung.c:samsung_nand_decode_id
  - drivers/mtd/nand/raw/nand_samsung.c:samsung_nand_decode_id
```
```
In drivers/mtd/nand/raw/nand_toshiba.c (c0aa8868)
Location: include/linux/mtd/rawnand.h:1272
Inline: True
```
</details>
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
