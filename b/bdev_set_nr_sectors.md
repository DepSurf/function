# Function: <code>bdev_set_nr_sectors</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81579976)
Location: block/partitions/core.c:89
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
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
In block/partitions/core.c (ffffffff81581636)
Location: block/partitions/core.c:89
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
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
In block/partitions/core.c (ffffffff815e6961)
Location: block/partitions/core.c:90
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
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
In block/partitions/core.c (ffffffff81695ad6)
Location: block/partitions/core.c:89
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81754d09)
Location: block/partitions/core.c:88
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bdev_set_nr_sectors(struct block_device *bdev, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766a70)
Location: block/bdev.c:435
Inline: False
Direct callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:blk_mark_disk_dead
  - block/genhd.c:set_capacity_and_notify
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff81766a70-ffffffff81766abe: bdev_set_nr_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bdev_set_nr_sectors(struct block_device *bdev, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a8690)
Location: block/bdev.c:424
Inline: False
Direct callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:__blk_mark_disk_dead
  - block/genhd.c:set_capacity_and_notify
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff817a8690-ffffffff817a86de: bdev_set_nr_sectors (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
