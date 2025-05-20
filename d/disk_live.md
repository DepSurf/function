# Function: <code>disk_live</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4c89)
Location: include/linux/genhd.h:167
Inline: True
```
```
In block/genhd.c (ffffffff815e35c6)
Location: include/linux/genhd.h:167
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff815e6819)
Location: include/linux/genhd.h:167
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f6bc)
Location: include/linux/blkdev.h:175
Inline: True
```
```
In block/genhd.c (ffffffff81692856)
Location: include/linux/blkdev.h:175
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff8169597a)
Location: include/linux/blkdev.h:175
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
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
In block/bdev.c (ffffffff8172aa9f)
Location: include/linux/blkdev.h:207
Inline: True
```
```
In block/genhd.c (ffffffff81750a96)
Location: include/linux/blkdev.h:207
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81754b8d)
Location: include/linux/blkdev.h:207
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In block/holder.c (ffffffff8178589e)
Location: include/linux/blkdev.h:207
Inline: True
Inline callers:
  - block/holder.c:bd_link_disk_holder
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
In block/bdev.c (ffffffff81766cde)
Location: include/linux/blkdev.h:212
Inline: True
```
```
In block/genhd.c (ffffffff8178ce96)
Location: include/linux/blkdev.h:212
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81790d88)
Location: include/linux/blkdev.h:212
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_add_partition
```
```
In block/blk-cgroup.c (ffffffff817a22e7)
Location: include/linux/blkdev.h:212
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
```
In block/holder.c (ffffffff817c5d08)
Location: include/linux/blkdev.h:212
Inline: True
Inline callers:
  - block/holder.c:bd_link_disk_holder
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
In block/bdev.c (ffffffff817a89a6)
Location: include/linux/blkdev.h:214
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
```
```
In block/genhd.c (ffffffff817cf6c6)
Location: include/linux/blkdev.h:214
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff817d48f4)
Location: include/linux/blkdev.h:214
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_add_partition
```
```
In block/blk-cgroup.c (ffffffff817e5e2a)
Location: include/linux/blkdev.h:214
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
```
In block/holder.c (ffffffff8180a9f8)
Location: include/linux/blkdev.h:214
Inline: True
Inline callers:
  - block/holder.c:bd_link_disk_holder
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
