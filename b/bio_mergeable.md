# Function: <code>bio_mergeable</code>

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
In block/elevator.c (ffffffff813b3d71)
Location: include/linux/bio.h:126
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff813c1b49)
Location: include/linux/bio.h:126
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff813c5fc9)
Location: include/linux/bio.h:126
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
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
In block/elevator.c (ffffffff813f7a51)
Location: include/linux/bio.h:99
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff81405b69)
Location: include/linux/bio.h:99
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff81409e57)
Location: include/linux/bio.h:99
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
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
In block/elevator.c (ffffffff81411481)
Location: include/linux/bio.h:94
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff8141fe12)
Location: include/linux/bio.h:94
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff814247dc)
Location: include/linux/bio.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
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
In block/elevator.c (ffffffff8141ef31)
Location: include/linux/bio.h:94
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff8142dd5f)
Location: include/linux/bio.h:94
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff8143137a)
Location: include/linux/bio.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/elevator.c (ffffffff81449a10)
Location: include/linux/bio.h:102
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff81458f8f)
Location: include/linux/bio.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff8145cd68)
Location: include/linux/bio.h:102
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/elevator.c (ffffffff8147c754)
Location: include/linux/bio.h:106
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:106
Inline: True
```
```
In block/blk-mq.c (ffffffff81490609)
Location: include/linux/bio.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/elevator.c (ffffffff8149a741)
Location: include/linux/bio.h:102
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:102
Inline: True
```
```
In block/blk-mq.c (ffffffff814aaa24)
Location: include/linux/bio.h:102
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/elevator.c (ffffffff814c880e)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffff814d84df)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff814e192e)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffff814f188f)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff8154049e)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff8154ce63)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff81550f74)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff8155cc3e)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff81569383)
Location: include/linux/bio.h:79
Inline: True
```
```
In block/blk-mq.c (ffffffff8156ee1f)
Location: include/linux/bio.h:79
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
In block/elevator.c (ffffffff815654e1)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff815712e3)
Location: include/linux/bio.h:82
Inline: True
```
```
In block/blk-mq.c (ffffffff815769fb)
Location: include/linux/bio.h:82
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
In block/elevator.c (ffffffff815c9871)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff815d5989)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffff815db6ab)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff81674b41)
Location: block/blk-mq-sched.h:38
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff81681739)
Location: block/blk-mq-sched.h:38
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff81682f82)
Location: block/blk-mq-sched.h:38
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
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
In block/elevator.c (ffffffff81730891)
Location: block/blk-mq-sched.h:38
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff8173ed09)
Location: block/blk-mq-sched.h:38
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff81740792)
Location: block/blk-mq-sched.h:38
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
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
In block/elevator.c (ffffffff8176caf4)
Location: block/blk-mq-sched.h:31
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff8177b279)
Location: block/blk-mq-sched.h:31
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff8177ca15)
Location: block/blk-mq-sched.h:31
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
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
In block/elevator.c (ffffffff817aed21)
Location: block/blk-mq-sched.h:31
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff817bd669)
Location: block/blk-mq-sched.h:31
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (ffffffff817bee12)
Location: block/blk-mq-sched.h:31
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
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
In block/elevator.c (ffff8000105dea48)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffff8000105f0f10)
Location: include/linux/bio.h:81
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
In block/elevator.c (c078b9e0)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (c0798270)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/blk-mq.c (c079cf9c)
Location: include/linux/bio.h:81
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
In block/elevator.c (c0000000007707a4)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (c000000000787bd0)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffe00042161c)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffe00042fbe6)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff814d9f0e)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffff814e9e6f)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff814ca8be)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffff814da3cf)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff814d5f9e)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffff814e5eff)
Location: include/linux/bio.h:81
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
In block/elevator.c (ffffffff814eeb9e)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:81
Inline: True
```
```
In block/blk-mq.c (ffffffff814fee6f)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
</ul>

## Differences
