# Function: <code>bdev_write_zeroes_sectors</code>

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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414c6a)
Location: include/linux/blkdev.h:1522
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-lib.c (ffffffff81420a32)
Location: include/linux/blkdev.h:1522
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
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
In block/blk-core.c (ffffffff814248f3)
Location: include/linux/blkdev.h:1547
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-lib.c (ffffffff8142e9a6)
Location: include/linux/blkdev.h:1547
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
```
```
In drivers/md/dm-kcopyd.c (ffffffff81758168)
Location: include/linux/blkdev.h:1547
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff81459e45)
Location: include/linux/blkdev.h:1562
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff817ca3d8)
Location: include/linux/blkdev.h:1562
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8148d59e)
Location: include/linux/blkdev.h:1603
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff818131d4)
Location: include/linux/blkdev.h:1603
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff814a6e2e)
Location: include/linux/blkdev.h:1382
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183f1af)
Location: include/linux/blkdev.h:1382
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff814d4d4e)
Location: include/linux/blkdev.h:1396
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881eab)
Location: include/linux/blkdev.h:1396
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff814ee03e)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3d4b)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff8154d9a7)
Location: include/linux/blkdev.h:1457
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff81984c48)
Location: include/linux/blkdev.h:1457
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff81569b27)
Location: include/linux/blkdev.h:1557
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff81988ce5)
Location: include/linux/blkdev.h:1557
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff81571a7e)
Location: include/linux/blkdev.h:1554
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196d3c5)
Location: include/linux/blkdev.h:1554
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff815d618e)
Location: include/linux/blkdev.h:1545
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a15488)
Location: include/linux/blkdev.h:1545
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff816821c4)
Location: include/linux/blkdev.h:1290
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm.c (ffffffff81b72fe0)
Location: include/linux/blkdev.h:1290
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7e2e4)
Location: include/linux/blkdev.h:1290
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8173f844)
Location: include/linux/blkdev.h:1238
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm.c (ffffffff81d0ef82)
Location: include/linux/blkdev.h:1238
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1c2f0)
Location: include/linux/blkdev.h:1238
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff8177bd81)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm.c (ffffffff81d78192)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d8546a)
Location: include/linux/blkdev.h:1219
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-lib.c (ffffffff817be171)
Location: include/linux/blkdev.h:1204
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm.c (ffffffff81e2f3cb)
Location: include/linux/blkdev.h:1204
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3cbec)
Location: include/linux/blkdev.h:1204
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffff8000105ecc34)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0bdd8)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (c0799148)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (c0be9874)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (c0000000007825fc)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (c000000000bfda00)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffe00042c6d0)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f932e)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff814e661e)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff81859bcb)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff814d6b8e)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff818211db)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff814e26ae)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a91fb)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In block/blk-lib.c (ffffffff814fb52e)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_write_zeroes
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c560b)
Location: include/linux/blkdev.h:1423
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
</ul>

## Differences
