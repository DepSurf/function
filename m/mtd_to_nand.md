# Function: <code>mtd_to_nand</code>

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
In drivers/mtd/nand/raw/nand_base.c (c0a9b5d4)
Location: include/linux/mtd/rawnand.h:1144
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_shutdown
  - drivers/mtd/nand/raw/nand_base.c:nand_resume
  - drivers/mtd/nand/raw/nand_base.c:nand_block_markbad
  - drivers/mtd/nand/raw/nand_base.c:nand_block_isbad
  - drivers/mtd/nand/raw/nand_base.c:nand_sync
  - drivers/mtd/nand/raw/nand_base.c:nand_erase
  - drivers/mtd/nand/raw/nand_base.c:panic_nand_write
  - drivers/mtd/nand/raw/nand_base.c:nand_block_isreserved
  - drivers/mtd/nand/raw/nand_base.c:nand_ooblayout_free_lp_hamming
  - drivers/mtd/nand/raw/nand_base.c:nand_ooblayout_free_lp
  - drivers/mtd/nand/raw/nand_base.c:nand_ooblayout_ecc_lp
```
```
In drivers/mtd/nand/raw/nand_micron.c (c0aa7bcc)
Location: include/linux/mtd/rawnand.h:1144
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_micron.c:micron_nand_on_die_8_ooblayout_free
  - drivers/mtd/nand/raw/nand_micron.c:micron_nand_on_die_8_ooblayout_ecc
```
```
In drivers/mtd/nand/raw/nand_bch.c (c0aa8ccc)
Location: include/linux/mtd/rawnand.h:1144
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_bch.c:nand_bch_init
```
```
In drivers/mtd/nand/raw/omap2.c (c0aa98cc)
Location: include/linux/mtd/rawnand.h:1144
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_remove
  - drivers/mtd/nand/raw/omap2.c:omap_nand_remove
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_sw_ooblayout_free
  - drivers/mtd/nand/raw/omap2.c:omap_sw_ooblayout_ecc
  - drivers/mtd/nand/raw/omap2.c:omap_ooblayout_free
  - drivers/mtd/nand/raw/omap2.c:omap_ooblayout_ecc
  - drivers/mtd/nand/raw/omap2.c:omap_elm_correct_data
  - drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc_bch_multi
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc_bch
  - drivers/mtd/nand/raw/omap2.c:omap_dev_ready
  - drivers/mtd/nand/raw/omap2.c:omap_wait
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc
  - drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc
  - drivers/mtd/nand/raw/omap2.c:omap_correct_data
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf16
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf8
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
