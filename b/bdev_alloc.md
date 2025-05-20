# Function: <code>bdev_alloc</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct block_device *bdev_alloc(struct gendisk *disk, u8 partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e6d0)
Location: fs/block_dev.c:880
Inline: False
Direct callers:
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff8136e6d0-ffffffff8136e7d2: bdev_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct block_device *bdev_alloc(struct gendisk *disk, u8 partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374fe0)
Location: fs/block_dev.c:886
Inline: False
Direct callers:
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff81374fe0-ffffffff813750e2: bdev_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct block_device *bdev_alloc(struct gendisk *disk, u8 partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c49c0)
Location: block/bdev.c:477
Inline: False
Direct callers:
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff815c49c0-ffffffff815c4a98: bdev_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct block_device *bdev_alloc(struct gendisk *disk, u8 partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f410)
Location: block/bdev.c:481
Inline: False
Direct callers:
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff8166f410-ffffffff8166f4dd: bdev_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct block_device *bdev_alloc(struct gendisk *disk, u8 partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a7a0)
Location: block/bdev.c:480
Inline: False
Direct callers:
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff8172a7a0-ffffffff8172a86d: bdev_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct block_device *bdev_alloc(struct gendisk *disk, u8 partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:402
Inline: False
Direct callers:
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff820f5879-ffffffff820f5894: bdev_alloc.cold (STB_LOCAL)
ffffffff81766930-ffffffff81766a51: bdev_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct block_device *bdev_alloc(struct gendisk *disk, u8 partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:391
Inline: False
Direct callers:
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff821d2b1f-ffffffff821d2b3a: bdev_alloc.cold (STB_LOCAL)
ffffffff817a8550-ffffffff817a8671: bdev_alloc (STB_GLOBAL)
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
