# Function: <code>mtd_set_ooblayout</code>

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
In drivers/mtd/mtdconcat.c (c0a92bf0)
Location: include/linux/mtd/mtd.h:362
Inline: True
Inline callers:
  - drivers/mtd/mtdconcat.c:mtd_concat_create
```
```
In drivers/mtd/mtdpart.c (c0a9442c)
Location: include/linux/mtd/mtd.h:362
Inline: True
Inline callers:
  - drivers/mtd/mtdpart.c:allocate_partition
```
```
In drivers/mtd/nand/raw/nand_base.c (c0aa22e4)
Location: include/linux/mtd/mtd.h:362
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
```
```
In drivers/mtd/nand/raw/nand_micron.c (c0aa7f60)
Location: include/linux/mtd/mtd.h:362
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_micron.c:micron_nand_init
  - drivers/mtd/nand/raw/nand_micron.c:micron_nand_init
```
```
In drivers/mtd/nand/raw/nand_toshiba.c (c0aa8918)
Location: include/linux/mtd/mtd.h:362
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (c0aabd20)
Location: include/linux/mtd/mtd.h:362
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
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
