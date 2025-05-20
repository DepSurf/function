# Function: <code>__blkdev_issue_write_same</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81420844)
Location: block/blk-lib.c:151
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
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
In block/blk-lib.c (ffffffff8142e7dc)
Location: block/blk-lib.c:146
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
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
In block/blk-lib.c (ffffffff81459afc)
Location: block/blk-lib.c:147
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
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
In block/blk-lib.c (ffffffff8148d166)
Location: block/blk-lib.c:166
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a6866)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d477b)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814eda8b)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __blkdev_issue_write_same(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct page *page, struct bio **biop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154db80)
Location: block/blk-lib.c:131
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
**Symbols:**

```
ffffffff8154db80-ffffffff8154dd8c: __blkdev_issue_write_same (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __blkdev_issue_write_same(struct block_device *bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct page *page, struct bio **biop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8156a040)
Location: block/blk-lib.c:165
Inline: False
Direct callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
**Symbols:**

```
ffffffff8156a040-ffffffff8156a246: __blkdev_issue_write_same (STB_LOCAL)
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
In block/blk-lib.c (ffffffff81572006)
Location: block/blk-lib.c:165
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
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
In block/blk-lib.c (ffffffff815d6716)
Location: block/blk-lib.c:166
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffff8000105ec680)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c0798b24)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (c000000000781dd4)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffe00042c218)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e606b)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814d65db)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814e20fb)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814fafa6)
Location: block/blk-lib.c:131
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
