# Function: <code>blk_rq_get_max_sectors</code>

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
In block/blk-merge.c (ffffffff813c0c97)
Location: include/linux/blkdev.h:889
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff8140513d)
Location: include/linux/blkdev.h:908
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-merge.c (ffffffff8141f073)
Location: include/linux/blkdev.h:1045
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814262e4)
Location: include/linux/blkdev.h:1078
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8142d525)
Location: include/linux/blkdev.h:1078
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff81451734)
Location: include/linux/blkdev.h:1091
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff81458775)
Location: include/linux/blkdev.h:1091
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814849b8)
Location: include/linux/blkdev.h:1126
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8148b4c9)
Location: include/linux/blkdev.h:1126
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff8149f94c)
Location: include/linux/blkdev.h:972
Inline: True
```
```
In block/blk-merge.c (ffffffff814a51a7)
Location: include/linux/blkdev.h:972
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814cda7f)
Location: include/linux/blkdev.h:1000
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d3286)
Location: include/linux/blkdev.h:1000
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814e6d9a)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814ec5b6)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff81545b49)
Location: include/linux/blkdev.h:1045
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8154bc83)
Location: include/linux/blkdev.h:1045
Inline: True
Inline callers:
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-merge.c (ffffffff81567765)
Location: include/linux/blkdev.h:1102
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-merge.c (ffffffff8156fdfe)
Location: include/linux/blkdev.h:1085
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff815d449f)
Location: include/linux/blkdev.h:1059
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff816802e5)
Location: block/blk-merge.c:559
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-merge.c (ffffffff8173d6b4)
Location: block/blk-merge.c:596
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-merge.c (ffffffff81779c34)
Location: block/blk-merge.c:590
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-merge.c (ffffffff817bc004)
Location: block/blk-merge.c:586
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-core.c (ffff8000105e46ec)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffff8000105eb03c)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (c0791948)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c0797580)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (c000000000778534)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c000000000780570)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffe000425e3a)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffe00042b25e)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814df37a)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e4b96)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814cfd1a)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d5340)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814db40a)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e0c26)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
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
In block/blk-core.c (ffffffff814f427a)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814f9aa6)
Location: include/linux/blkdev.h:1023
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
</details>
</li>
</ul>

## Differences
