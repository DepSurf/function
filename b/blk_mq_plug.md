# Function: <code>blk_mq_plug</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cdbd5)
Location: block/blk-mq.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff814d85e5)
Location: block/blk-mq.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814e6ef5)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff814f1995)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff81545cb5)
Location: block/blk-mq.h:245
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff815510ba)
Location: block/blk-mq.h:245
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff8155ffd1)
Location: block/blk-mq.h:271
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-merge.c (ffffffff81569555)
Location: block/blk-mq.h:271
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff8156ef6b)
Location: block/blk-mq.h:271
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-core.c (ffffffff8156818c)
Location: block/blk-mq.h:289
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-merge.c (ffffffff815714c5)
Location: block/blk-mq.h:289
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff81576b56)
Location: block/blk-mq.h:289
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-core.c (ffffffff815cc77c)
Location: block/blk-mq.h:293
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-merge.c (ffffffff815d5b85)
Location: block/blk-mq.h:293
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff815db806)
Location: block/blk-mq.h:293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-core.c (ffffffff81679389)
Location: block/blk-mq.h:312
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff81681905)
Location: block/blk-mq.h:312
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff81689746)
Location: block/blk-mq.h:312
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-core.c (ffffffff81735809)
Location: block/blk-mq.h:312
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff8173ef05)
Location: block/blk-mq.h:312
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff81747bf4)
Location: block/blk-mq.h:312
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-merge.c (ffffffff8177b475)
Location: block/blk-mq.h:362
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff817842a4)
Location: block/blk-mq.h:362
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-merge.c (ffffffff817bd865)
Location: block/blk-mq.h:385
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff817c65b2)
Location: block/blk-mq.h:385
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-core.c (ffff8000105e487c)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffff8000105f1038)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (c0791aa0)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (c079d0d4)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (c0000000007786ec)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (c000000000787d3c)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffe000425f9a)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffe00042fcee)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814df4d5)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff814e9f75)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814cfe75)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff814da4d5)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814db565)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff814e6005)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff814f43d5)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff814fef75)
Location: block/blk-mq.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
</ul>

## Differences
