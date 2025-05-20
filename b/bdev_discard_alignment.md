# Function: <code>bdev_discard_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff813c26d7)
Location: include/linux/blkdev.h:1295
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81406356)
Location: include/linux/blkdev.h:1324
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81420615)
Location: include/linux/blkdev.h:1489
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8142e5ab)
Location: include/linux/blkdev.h:1527
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814597ab)
Location: include/linux/blkdev.h:1542
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148cd53)
Location: include/linux/blkdev.h:1583
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int bdev_discard_alignment(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167d3b0)
Location: block/blk-settings.c:966
Inline: False
Direct callers:
  - block/partitions/core.c:part_discard_alignment_show
```
**Symbols:**

```
ffffffff8167d3b0-ffffffff8167d42e: bdev_discard_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int bdev_discard_alignment(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739e70)
Location: block/blk-settings.c:968
Inline: False
Direct callers:
  - block/partitions/core.c:part_discard_alignment_show
```
**Symbols:**

```
ffffffff81739e70-ffffffff81739eee: bdev_discard_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int bdev_discard_alignment(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81776550)
Location: block/blk-settings.c:978
Inline: False
Direct callers:
  - block/partitions/core.c:part_discard_alignment_show
```
**Symbols:**

```
ffffffff81776550-ffffffff817765c8: bdev_discard_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int bdev_discard_alignment(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b8880)
Location: block/blk-settings.c:919
Inline: False
Direct callers:
  - block/partitions/core.c:part_discard_alignment_show
```
**Symbols:**

```
ffffffff817b8880-ffffffff817b88f8: bdev_discard_alignment (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
