# Function: <code>nand_to_mtd</code>

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
In drivers/mtd/nand/raw/nand_base.c (c0a9b938)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_release
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
  - drivers/mtd/nand/raw/nand_base.c:nand_write_subpage_hwecc
  - drivers/mtd/nand/raw/nand_base.c:nand_write_page_hwecc
  - drivers/mtd/nand/raw/nand_base.c:nand_transfer_oob
  - drivers/mtd/nand/raw/nand_base.c:nand_read_page_hwecc_oob_first
  - drivers/mtd/nand/raw/nand_base.c:nand_read_page_hwecc
  - drivers/mtd/nand/raw/nand_base.c:nand_read_subpage
  - drivers/mtd/nand/raw/nand_base.c:nand_read_page_swecc
  - drivers/mtd/nand/raw/nand_base.c:nand_fill_oob
```
```
In drivers/mtd/nand/raw/nand_legacy.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/nand_bbt.c (c0aa4610)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_bbt.c:write_bbt
  - drivers/mtd/nand/raw/nand_bbt.c:create_bbt
  - drivers/mtd/nand/raw/nand_bbt.c:read_bbt
```
```
In drivers/mtd/nand/raw/nand_onfi.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/nand_jedec.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/nand_amd.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/nand_hynix.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/nand_micron.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/nand_samsung.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/nand_toshiba.c (0)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (c0aab9fc)
Location: include/linux/mtd/rawnand.h:1149
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_read_page_bch
  - drivers/mtd/nand/raw/omap2.c:omap_write_subpage_bch
  - drivers/mtd/nand/raw/omap2.c:omap_write_page_bch
  - drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc_bch_sw
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref
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
