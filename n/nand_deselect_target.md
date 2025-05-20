# Function: <code>nand_deselect_target</code>

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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nand_deselect_target(struct nand_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mtd/nand/raw/nand_base.c (c0aa1800)
Location: drivers/mtd/nand/raw/nand_base.c:259
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
  - drivers/mtd/nand/raw/nand_base.c:rawnand_isbad
  - drivers/mtd/nand/raw/nand_base.c:rawnand_erase
  - drivers/mtd/nand/raw/nand_base.c:nand_block_isbad
  - drivers/mtd/nand/raw/nand_base.c:nand_erase_nand
  - drivers/mtd/nand/raw/nand_base.c:nand_erase_nand
  - drivers/mtd/nand/raw/nand_base.c:nand_do_write_ops
  - drivers/mtd/nand/raw/nand_base.c:nand_do_write_ops
  - drivers/mtd/nand/raw/nand_base.c:nand_do_read_ops
  - drivers/mtd/nand/raw/nand_base.c:nand_do_read_ops
  - drivers/mtd/nand/raw/nand_base.c:nand_reset
  - drivers/mtd/nand/raw/nand_base.c:nand_setup_data_interface
  - drivers/mtd/nand/raw/nand_base.c:nand_setup_data_interface
  - drivers/mtd/nand/raw/nand_base.c:nand_setup_data_interface
  - drivers/mtd/nand/raw/nand_base.c:nand_do_write_oob
  - drivers/mtd/nand/raw/nand_base.c:nand_do_write_oob
```
**Symbols:**

```
c0a9a268-c0a9a2a0: nand_deselect_target (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
