# Function: <code>trace_block_split</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81404755)
Location: include/trace/events/block.h:557
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff8141deb4)
Location: include/trace/events/block.h:551
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff8142c264)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff81457474)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
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
In block/blk-merge.c (ffffffff8148a383)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff814a3f67)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In drivers/md/dm.c (ffffffff81834925)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff814d283f)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff81876cc7)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff814ebbc8)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff818a8be7)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff8154bf1d)
Location: include/trace/events/block.h:518
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff819796e2)
Location: include/trace/events/block.h:518
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff8156828f)
Location: include/trace/events/block.h:418
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff8197d3d2)
Location: include/trace/events/block.h:418
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff81570056)
Location: include/trace/events/block.h:418
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff819614b1)
Location: include/trace/events/block.h:418
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff815d46fa)
Location: include/trace/events/block.h:418
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff81a0b0c8)
Location: include/trace/events/block.h:418
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff816804ed)
Location: include/trace/events/block.h:441
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff81b72a82)
Location: include/trace/events/block.h:441
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In block/blk-merge.c (ffffffff8173d90f)
Location: include/trace/events/block.h:441
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
```
In drivers/md/dm.c (ffffffff81d0f910)
Location: include/trace/events/block.h:441
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In block/blk-merge.c (ffffffff81779e8c)
Location: include/trace/events/block.h:467
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
```
In drivers/md/dm.c (ffffffff81d78d15)
Location: include/trace/events/block.h:467
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In block/blk-merge.c (ffffffff817bc26c)
Location: include/trace/events/block.h:469
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
```
In drivers/md/dm.c (ffffffff81e2fe37)
Location: include/trace/events/block.h:469
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In block/blk-merge.c (ffff8000105ea574)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffff800010aff560)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (c07969f8)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (c0bdea00)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (c00000000077f6e0)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (c000000000bedad4)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffe00042a90e)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffe0006eedf6)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff814e41a8)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff8184ea67)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff814d4a88)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff81816087)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff814e0238)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff8189e097)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-merge.c (ffffffff814f9098)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In drivers/md/dm.c (ffffffff818baf27)
Location: include/trace/events/block.h:519
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
</details>
</li>
</ul>

## Differences
