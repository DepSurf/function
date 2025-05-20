# Function: <code>part_nr_sects_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (0)
Location: include/linux/genhd.h:700
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:700
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:700
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (0)
Location: include/linux/genhd.h:689
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:689
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:689
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (0)
Location: include/linux/genhd.h:680
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:680
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:680
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/genhd.c (0)
Location: include/linux/genhd.h:674
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:674
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:683
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:683
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:683
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:692
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:692
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:692
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:692
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:715
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:715
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:715
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:715
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f450)
Location: block/blk.h:393
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffff81544b3a)
Location: block/blk.h:393
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/genhd.c (ffffffff81559205)
Location: block/blk.h:393
Inline: True
Inline callers:
  - block/genhd.c:part_size_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
sector_t part_nr_sects_read(struct hd_struct *part);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
```
```
In block/blk-core.c (c078f278)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/genhd.c (c07a5b90)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
Direct callers:
  - block/genhd.c:printk_all_partitions
```
```
In block/partition-generic.c (c07a767c)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/partition-generic.c:part_size_show
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
**Symbols:**

```
c07a457c-c07a45ec: part_nr_sects_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dff3c)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
```
```
In block/blk-core.c (c0000000007754f0)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/genhd.c (c00000000139ee78)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
```
```
In block/partition-generic.c (c000000000795bdc)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/partition-generic.c:part_size_show
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe00029377a)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
```
```
In block/blk-core.c (ffffffe00042419a)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/genhd.c (ffffffe00002947e)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
```
```
In block/partition-generic.c (ffffffe000438512)
Location: include/linux/genhd.h:723
Inline: True
Inline callers:
  - block/partition-generic.c:part_size_show
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/genhd.h:723
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
