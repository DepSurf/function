# Function: <code>bio_allowed_max_sectors</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a4121)
Location: block/blk.h:239
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-lib.c (ffffffff814a68c6)
Location: block/blk.h:239
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d2917)
Location: block/blk.h:258
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814d47dc)
Location: block/blk.h:258
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ebc8f)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814edaea)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154bfb4)
Location: block/blk.h:279
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff8154dc0b)
Location: block/blk.h:279
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156830e)
Location: block/blk.h:256
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff8156a0c5)
Location: block/blk.h:256
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815700d6)
Location: block/blk.h:260
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff81572060)
Location: block/blk.h:260
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d477f)
Location: block/blk.h:264
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff815d6770)
Location: block/blk.h:264
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
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
In block/blk-merge.c (ffffffff816805b6)
Location: block/blk.h:344
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-merge.c (ffffffff8173d99a)
Location: block/blk-merge.c:103
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
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
In block/blk-merge.c (ffffffff81779f2f)
Location: block/blk-merge.c:103
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bc30f)
Location: block/blk-merge.c:103
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ea6a4)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffff8000105ec6b8)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0796110)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_discard_split
```
```
In block/blk-lib.c (c0798b6c)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c00000000077f724)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (c000000000781e28)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042a9fa)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffe00042c24e)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e426f)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814e60ca)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d4b4f)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814d663a)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e02ff)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814e215a)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f915f)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-lib.c (ffffffff814fb003)
Location: block/blk.h:272
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
</details>
</li>
</ul>

## Differences
