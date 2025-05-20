# Function: <code>mtd_to_part</code>

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
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mtd/mtdpart.c (c0a938f4)
Location: drivers/mtd/mtdpart.c:45
Inline: True
Inline callers:
  - drivers/mtd/mtdpart.c:mtd_partition_offset_show
  - drivers/mtd/mtdpart.c:part_max_bad_blocks
  - drivers/mtd/mtdpart.c:part_ooblayout_free
  - drivers/mtd/mtdpart.c:part_ooblayout_ecc
  - drivers/mtd/mtdpart.c:part_put_device
  - drivers/mtd/mtdpart.c:part_get_device
  - drivers/mtd/mtdpart.c:part_block_markbad
  - drivers/mtd/mtdpart.c:part_block_isbad
  - drivers/mtd/mtdpart.c:part_block_isreserved
  - drivers/mtd/mtdpart.c:part_resume
  - drivers/mtd/mtdpart.c:part_suspend
  - drivers/mtd/mtdpart.c:part_sync
  - drivers/mtd/mtdpart.c:part_is_locked
  - drivers/mtd/mtdpart.c:part_unlock
  - drivers/mtd/mtdpart.c:part_lock
  - drivers/mtd/mtdpart.c:part_erase
  - drivers/mtd/mtdpart.c:part_writev
  - drivers/mtd/mtdpart.c:part_lock_user_prot_reg
  - drivers/mtd/mtdpart.c:part_write_user_prot_reg
  - drivers/mtd/mtdpart.c:part_write_oob
  - drivers/mtd/mtdpart.c:part_panic_write
  - drivers/mtd/mtdpart.c:part_write
  - drivers/mtd/mtdpart.c:part_get_fact_prot_info
  - drivers/mtd/mtdpart.c:part_read_fact_prot_reg
  - drivers/mtd/mtdpart.c:part_get_user_prot_info
  - drivers/mtd/mtdpart.c:part_read_user_prot_reg
  - drivers/mtd/mtdpart.c:part_read_oob
  - drivers/mtd/mtdpart.c:part_unpoint
  - drivers/mtd/mtdpart.c:part_point
  - drivers/mtd/mtdpart.c:part_read
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
