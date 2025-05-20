# Function: <code>blk_queue_get_max_sectors</code>

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
In block/blk-core.c (ffffffff813badfe)
Location: include/linux/blkdev.h:863
Inline: True
```
```
In block/blk-merge.c (ffffffff813c0cb6)
Location: include/linux/blkdev.h:863
Inline: True
Inline callers:
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
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
In block/blk-core.c (ffffffff813feb9f)
Location: include/linux/blkdev.h:882
Inline: True
```
```
In block/blk-merge.c (ffffffff81405176)
Location: include/linux/blkdev.h:882
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff8141858b)
Location: include/linux/blkdev.h:1016
Inline: True
```
```
In block/blk-merge.c (ffffffff8141f0a9)
Location: include/linux/blkdev.h:1016
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff81426321)
Location: include/linux/blkdev.h:1049
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8142d6b4)
Location: include/linux/blkdev.h:1049
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff81451771)
Location: include/linux/blkdev.h:1062
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff81458904)
Location: include/linux/blkdev.h:1062
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff814849f5)
Location: include/linux/blkdev.h:1096
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8148b502)
Location: include/linux/blkdev.h:1096
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff8149fbc9)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
```
```
In block/blk-merge.c (ffffffff814a51e0)
Location: include/linux/blkdev.h:942
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff814cdd03)
Location: include/linux/blkdev.h:970
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d32c3)
Location: include/linux/blkdev.h:970
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff814e7023)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814ec5f3)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff81545f83)
Location: include/linux/blkdev.h:1015
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8154bd9c)
Location: include/linux/blkdev.h:1015
Inline: True
Inline callers:
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff81561da6)
Location: include/linux/blkdev.h:1063
Inline: True
```
```
In block/blk-merge.c (ffffffff8156786e)
Location: include/linux/blkdev.h:1063
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff8156a513)
Location: include/linux/blkdev.h:1046
Inline: True
```
```
In block/blk-merge.c (ffffffff8156fefe)
Location: include/linux/blkdev.h:1046
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-core.c (ffffffff815cea13)
Location: include/linux/blkdev.h:1020
Inline: True
```
```
In block/blk-merge.c (ffffffff815d459d)
Location: include/linux/blkdev.h:1020
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff8168032f)
Location: include/linux/blkdev.h:919
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81687faa)
Location: include/linux/blkdev.h:919
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
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
In block/blk-merge.c (ffffffff8173d6be)
Location: block/blk.h:159
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8174638a)
Location: block/blk.h:159
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
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
In block/blk-merge.c (ffffffff81779c3e)
Location: block/blk.h:170
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff8178372a)
Location: block/blk.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
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
In block/blk-merge.c (ffffffff817bc00e)
Location: block/blk.h:169
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff817c5a9a)
Location: block/blk.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
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
In block/blk-core.c (ffff8000105e49c8)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffff8000105eb054)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (c0791bf8)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c07975ac)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (c0000000007788c8)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c0000000007805bc)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffe00042608c)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffe00042b2a4)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff814df603)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e4bd3)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff814cffa3)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d537e)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff814db693)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e0c63)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffffffff814f4503)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814f9ae3)
Location: include/linux/blkdev.h:993
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
</details>
</li>
</ul>

## Differences
