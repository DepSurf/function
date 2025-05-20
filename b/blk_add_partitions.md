# Function: <code>blk_add_partitions</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int blk_add_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:691
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
```
**Symbols:**

```
ffffffff8155dfa3-ffffffff8155e008: blk_add_partitions.cold (STB_LOCAL)
ffffffff8155dc30-ffffffff8155dd61: blk_add_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int blk_add_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:615
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
```
**Symbols:**

```
ffffffff81bf2a99-ffffffff81bf2afe: blk_add_partitions.cold (STB_LOCAL)
ffffffff81579a40-ffffffff81579b6c: blk_add_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int blk_add_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:601
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
```
**Symbols:**

```
ffffffff81be49dc-ffffffff81be4b02: blk_add_partitions.cold (STB_LOCAL)
ffffffff81581720-ffffffff81581895: blk_add_partitions (STB_GLOBAL)
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
In block/partitions/core.c (ffffffff815e6af2)
Location: block/partitions/core.c:604
Inline: True
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
In block/partitions/core.c (ffffffff81695c58)
Location: block/partitions/core.c:592
Inline: True
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
In block/partitions/core.c (ffffffff81754ec6)
Location: block/partitions/core.c:591
Inline: True
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
In block/partitions/core.c (ffffffff81790ebd)
Location: block/partitions/core.c:588
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blk_add_partitions(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:582
Inline: False
Direct callers:
  - block/partitions/core.c:bdev_disk_changed
```
**Symbols:**

```
ffffffff817d4630-ffffffff817d48aa: blk_add_partitions (STB_LOCAL)
ffffffff821d3d6b-ffffffff821d3d95: blk_add_partitions.cold (STB_LOCAL)
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
</ul>
