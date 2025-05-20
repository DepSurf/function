# Function: <code>bdev_resize_partition</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdev_resize_partition(struct block_device *bdev, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff8155da50)
Location: block/partitions/core.c:560
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff8155da50-ffffffff8155db51: bdev_resize_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_resize_partition(struct block_device *bdev, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815798c0)
Location: block/partitions/core.c:496
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff815798c0-ffffffff815799ad: bdev_resize_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdev_resize_partition(struct block_device *bdev, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81581580)
Location: block/partitions/core.c:490
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81581580-ffffffff81581669: bdev_resize_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bdev_resize_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815e6900)
Location: block/partitions/core.c:500
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff815e6900-ffffffff815e69bb: bdev_resize_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bdev_resize_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81695a70)
Location: block/partitions/core.c:491
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81695a70-ffffffff81695b3f: bdev_resize_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bdev_resize_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81754ca0)
Location: block/partitions/core.c:490
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81754ca0-ffffffff81754d72: bdev_resize_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bdev_resize_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81791400)
Location: block/partitions/core.c:498
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81791400-ffffffff817914ae: bdev_resize_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bdev_resize_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff817d4d00)
Location: block/partitions/core.c:492
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff817d4d00-ffffffff817d4dae: bdev_resize_partition (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
