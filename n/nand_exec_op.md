# Function: <code>nand_exec_op</code>

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
In drivers/mtd/nand/raw/nand_base.c (c0aa09ec)
Location: drivers/mtd/nand/raw/internals.h:108
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_set_features
  - drivers/mtd/nand/raw/nand_base.c:nand_set_features
  - drivers/mtd/nand/raw/nand_base.c:nand_get_features
  - drivers/mtd/nand/raw/nand_base.c:nand_get_features
  - drivers/mtd/nand/raw/nand_base.c:nand_erase_op
  - drivers/mtd/nand/raw/nand_base.c:nand_erase_op
  - drivers/mtd/nand/raw/nand_base.c:nand_readid_op
  - drivers/mtd/nand/raw/nand_base.c:nand_readid_op
  - drivers/mtd/nand/raw/nand_base.c:nand_change_write_column_op
  - drivers/mtd/nand/raw/nand_base.c:nand_change_write_column_op
  - drivers/mtd/nand/raw/nand_base.c:nand_prog_page_end_op
  - drivers/mtd/nand/raw/nand_base.c:nand_prog_page_end_op
  - drivers/mtd/nand/raw/nand_base.c:nand_exec_prog_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_exec_prog_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_change_read_column_op
  - drivers/mtd/nand/raw/nand_base.c:nand_change_read_column_op
  - drivers/mtd/nand/raw/nand_base.c:nand_read_param_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_read_param_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_read_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_read_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_lp_exec_read_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_lp_exec_read_page_op
```
```
In drivers/mtd/nand/raw/nand_hynix.c (c0aa6f24)
Location: drivers/mtd/nand/raw/internals.h:108
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_hynix.c:hynix_nand_reg_write_op
  - drivers/mtd/nand/raw/nand_hynix.c:hynix_nand_reg_write_op
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
