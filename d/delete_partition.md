# Function: <code>delete_partition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff813cd200)
Location: block/partition-generic.c:241
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff813cd200-ffffffff813cd25d: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81411640)
Location: block/partition-generic.c:253
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81411640-ffffffff8141169d: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8142c9d0)
Location: block/partition-generic.c:253
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8142c9d0-ffffffff8142ca2d: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81439ce0)
Location: block/partition-generic.c:252
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81439ce0-ffffffff81439d3e: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81465d00)
Location: block/partition-generic.c:260
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81465d00-ffffffff81465d5e: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814996f0)
Location: block/partition-generic.c:267
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814996f0-ffffffff8149974d: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814b3950)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814b3950-ffffffff814b39ad: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e1ee0)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814e1ee0-ffffffff814e1f48: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814fb2a0)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814fb2a0-ffffffff814fb308: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff8155d820)
Location: block/partitions/core.c:313
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff8155d820-ffffffff8155d8a7: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void delete_partition(struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81579700)
Location: block/partitions/core.c:290
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff81579700-ffffffff8157977b: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void delete_partition(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81580ed0)
Location: block/partitions/core.c:288
Inline: False
Direct callers:
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff81580ed0-ffffffff81580f4e: delete_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void delete_partition(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815e61e0)
Location: block/partitions/core.c:284
Inline: False
Direct callers:
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff815e61e0-ffffffff815e625e: delete_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void delete_partition(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81695300)
Location: block/partitions/core.c:275
Inline: False
Direct callers:
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff81695300-ffffffff8169538a: delete_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void delete_partition(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff817543d0)
Location: block/partitions/core.c:274
Inline: False
Direct callers:
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff817543d0-ffffffff8175445a: delete_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81790df8)
Location: block/partitions/core.c:277
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffff8000105fd290)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffff8000105fd290-ffff8000105fd300: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c07a819c)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c07a819c-c07a8204: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c000000000796a50)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c000000000796a50-c000000000796ae8: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffe000438ed2)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffe000438ed2-ffffffe000438f4a: delete_partition (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814f3880)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814f3880-ffffffff814f38e8: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e3d90)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814e3d90-ffffffff814e3df8: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814ef910)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814ef910-ffffffff814ef978: delete_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void delete_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff815089a0)
Location: block/partition-generic.c:270
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff815089a0-ffffffff81508a08: delete_partition (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hd_struct *part</code>
</li>
<li>
<b>Param removed. </b>
<code>int partno</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>disk, part</code> ➡️ <code>part</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct hd_struct *part</code> ➡️ <code>struct block_device *part</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
