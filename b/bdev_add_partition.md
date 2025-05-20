# Function: <code>bdev_add_partition</code>

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
int bdev_add_partition(struct block_device *bdev, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff8155d8b0)
Location: block/partitions/core.c:507
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff8155d8b0-ffffffff8155d944: bdev_add_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_add_partition(struct block_device *bdev, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81579780)
Location: block/partitions/core.c:451
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81579780-ffffffff81579814: bdev_add_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdev_add_partition(struct block_device *bdev, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81581450)
Location: block/partitions/core.c:448
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81581450-ffffffff815814e1: bdev_add_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bdev_add_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815e67f0)
Location: block/partitions/core.c:454
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff815e67f0-ffffffff815e688d: bdev_add_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bdev_add_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81695950)
Location: block/partitions/core.c:445
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81695950-ffffffff816959fc: bdev_add_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bdev_add_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81754b60)
Location: block/partitions/core.c:444
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81754b60-ffffffff81754c0f: bdev_add_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bdev_add_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81791200)
Location: block/partitions/core.c:441
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81791200-ffffffff817912e1: bdev_add_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bdev_add_partition(struct gendisk *disk, int partno, sector_t start, sector_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff817d4b10)
Location: block/partitions/core.c:419
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff817d4b10-ffffffff817d4c0a: bdev_add_partition (STB_GLOBAL)
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
