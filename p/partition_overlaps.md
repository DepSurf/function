# Function: <code>partition_overlaps</code>

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
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff8155cfb0)
Location: block/partitions/core.c:486
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff8155cfb0-ffffffff8155d04f: partition_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815790c0)
Location: block/partitions/core.c:430
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff815790c0-ffffffff8157916a: partition_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81580df0)
Location: block/partitions/core.c:427
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff81580df0-ffffffff81580ec1: partition_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815e6100)
Location: block/partitions/core.c:433
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff815e6100-ffffffff815e61d1: partition_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81695210)
Location: block/partitions/core.c:424
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff81695210-ffffffff816952f2: partition_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff817542d0)
Location: block/partitions/core.c:423
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff817542d0-ffffffff817543b2: partition_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81790490)
Location: block/partitions/core.c:420
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff81790490-ffffffff8179056f: partition_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool partition_overlaps(struct gendisk *disk, sector_t start, sector_t length, int skip_partno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff817d3d30)
Location: block/partitions/core.c:398
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_add_partition
```
**Symbols:**

```
ffffffff817d3d30-ffffffff817d3e0f: partition_overlaps (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
