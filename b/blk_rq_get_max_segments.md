# Function: <code>blk_rq_get_max_segments</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154bd07)
Location: block/blk-merge.c:537
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
In block/blk-merge.c (ffffffff81567a0f)
Location: block/blk-merge.c:553
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff81570dcf)
Location: block/blk-merge.c:552
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff815d547a)
Location: block/blk-merge.c:554
Inline: True
Inline callers:
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
In block/blk-merge.c (ffffffff816812a7)
Location: block/blk-merge.c:552
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
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
In block/blk-merge.c (ffffffff8173e803)
Location: block/blk-merge.c:589
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-merge.c (ffffffff8177ad63)
Location: block/blk.h:163
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff81783746)
Location: block/blk.h:163
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
In block/blk-merge.c (ffffffff817bd144)
Location: block/blk.h:162
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-mq.c (ffffffff817c5ab6)
Location: block/blk.h:162
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
