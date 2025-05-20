# Function: <code>bdev_write_same</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b6166)
Location: include/linux/blkdev.h:1318
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-lib.c (ffffffff813c2a85)
Location: include/linux/blkdev.h:1318
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
```
```
In drivers/md/dm-kcopyd.c (ffffffff816abdff)
Location: include/linux/blkdev.h:1318
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fb26c)
Location: include/linux/blkdev.h:1347
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-lib.c (ffffffff814066bc)
Location: include/linux/blkdev.h:1347
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
```
```
In drivers/md/dm-kcopyd.c (ffffffff8170c31b)
Location: include/linux/blkdev.h:1347
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414a63)
Location: include/linux/blkdev.h:1512
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-lib.c (0)
Location: include/linux/blkdev.h:1512
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff8173e34b)
Location: include/linux/blkdev.h:1512
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424921)
Location: include/linux/blkdev.h:1537
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-lib.c (0)
Location: include/linux/blkdev.h:1537
Inline: True
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
In block/blk-lib.c (0)
Location: include/linux/blkdev.h:1552
Inline: True
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
In block/blk-lib.c (ffffffff8148d1b4)
Location: include/linux/blkdev.h:1593
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
In block/blk-lib.c (ffffffff814a68b8)
Location: include/linux/blkdev.h:1372
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
In block/blk-lib.c (ffffffff814d47ce)
Location: include/linux/blkdev.h:1386
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
In block/blk-lib.c (ffffffff814edadc)
Location: include/linux/blkdev.h:1413
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8154dbfd)
Location: include/linux/blkdev.h:1447
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_write_same
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8156a0b7)
Location: include/linux/blkdev.h:1547
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_write_same
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
In block/blk-lib.c (ffffffff81572052)
Location: include/linux/blkdev.h:1544
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
In block/blk-lib.c (ffffffff815d6762)
Location: include/linux/blkdev.h:1535
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
In block/blk-lib.c (ffff8000105ec6b0)
Location: include/linux/blkdev.h:1413
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
In block/blk-lib.c (c0798b60)
Location: include/linux/blkdev.h:1413
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
In block/blk-lib.c (c000000000781e14)
Location: include/linux/blkdev.h:1413
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
In block/blk-lib.c (ffffffe00042c246)
Location: include/linux/blkdev.h:1413
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
In block/blk-lib.c (ffffffff814e60bc)
Location: include/linux/blkdev.h:1413
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
In block/blk-lib.c (ffffffff814d662c)
Location: include/linux/blkdev.h:1413
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
In block/blk-lib.c (ffffffff814e214c)
Location: include/linux/blkdev.h:1413
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
In block/blk-lib.c (ffffffff814faff5)
Location: include/linux/blkdev.h:1413
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_write_same
```
</details>
</li>
</ul>

## Differences
