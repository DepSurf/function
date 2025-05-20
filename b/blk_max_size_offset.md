# Function: <code>blk_max_size_offset</code>

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
In block/blk-merge.c (ffffffff813c05f1)
Location: include/linux/blkdev.h:879
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:attempt_merge
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
In block/blk-merge.c (ffffffff8140516b)
Location: include/linux/blkdev.h:898
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff8141f09f)
Location: include/linux/blkdev.h:1035
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
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
In block/blk-core.c (ffffffff81426316)
Location: include/linux/blkdev.h:1068
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8142d9f6)
Location: include/linux/blkdev.h:1068
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
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
In block/blk-core.c (ffffffff81451766)
Location: include/linux/blkdev.h:1081
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff81458c2a)
Location: include/linux/blkdev.h:1081
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
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
In block/blk-core.c (ffffffff814849e5)
Location: include/linux/blkdev.h:1116
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8148b4ef)
Location: include/linux/blkdev.h:1116
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
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
In block/blk-core.c (ffffffff8149f97b)
Location: include/linux/blkdev.h:962
Inline: True
```
```
In block/blk-merge.c (ffffffff814a51cd)
Location: include/linux/blkdev.h:962
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
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
In block/blk-core.c (ffffffff814cdab2)
Location: include/linux/blkdev.h:990
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d32b0)
Location: include/linux/blkdev.h:990
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff814e6dcd)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814ec5e0)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff81545b6e)
Location: include/linux/blkdev.h:1035
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8154bcad)
Location: include/linux/blkdev.h:1035
Inline: True
Inline callers:
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
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
In block/blk-merge.c (ffffffff8156779f)
Location: include/linux/blkdev.h:1083
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In drivers/md/dm.c (ffffffff8197c397)
Location: include/linux/blkdev.h:1083
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
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
In block/blk-merge.c (ffffffff8156fe2f)
Location: include/linux/blkdev.h:1066
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
```
```
In drivers/md/dm.c (ffffffff81960027)
Location: include/linux/blkdev.h:1066
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
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
In block/blk-merge.c (ffffffff815d44cf)
Location: include/linux/blkdev.h:1040
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
```
```
In drivers/md/dm.c (ffffffff81a07ff7)
Location: include/linux/blkdev.h:1040
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
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
In block/blk-merge.c (ffffffff8168030c)
Location: include/linux/blkdev.h:936
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In drivers/md/dm.c (ffffffff81b6fc00)
Location: include/linux/blkdev.h:936
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e47d4)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffff8000105eb1bc)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (c0791a10)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c0797840)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (c000000000778558)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c000000000780594)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffe000425e64)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffe00042b286)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff814df3ad)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e4bc0)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff814cfd4d)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d536c)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff814db43d)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e0c50)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff814f42ad)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814f9ad0)
Location: include/linux/blkdev.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
</details>
</li>
</ul>

## Differences
