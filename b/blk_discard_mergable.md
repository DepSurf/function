# Function: <code>blk_discard_mergable</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a6185)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff814d4075)
Location: block/blk-merge.c:648
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff814ed3a5)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff8154cf35)
Location: block/blk-merge.c:698
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff81568aee)
Location: block/blk-merge.c:713
Inline: True
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
In block/blk-merge.c (ffffffff81570672)
Location: block/blk-merge.c:716
Inline: True
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
In block/elevator.c (ffffffff815c98c4)
Location: include/linux/blkdev.h:1517
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff815d4d22)
Location: include/linux/blkdev.h:1517
Inline: True
```
```
In block/mq-deadline.c (ffffffff81601501)
Location: include/linux/blkdev.h:1517
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
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
In block/elevator.c (ffffffff81674b95)
Location: block/blk.h:154
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff81680b80)
Location: block/blk.h:154
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/mq-deadline.c (ffffffff816b3dad)
Location: block/blk.h:154
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
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
In block/elevator.c (ffffffff817308e5)
Location: block/blk.h:151
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff8173e054)
Location: block/blk.h:151
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/mq-deadline.c (ffffffff817734eb)
Location: block/blk.h:151
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
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
In block/elevator.c (ffffffff8176cb4b)
Location: block/blk.h:155
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff8177a5a4)
Location: block/blk.h:155
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/mq-deadline.c (ffffffff817b238b)
Location: block/blk.h:155
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
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
In block/elevator.c (ffffffff817aed76)
Location: block/blk.h:154
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-merge.c (ffffffff817bc984)
Location: block/blk.h:154
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/mq-deadline.c (ffffffff817f619b)
Location: block/blk.h:154
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
```
</details>
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
In block/blk-merge.c (ffff8000105ebe6c)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (c0798370)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (c000000000781378)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffe00042bb88)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff814e5985)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff814d5f35)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff814e1a15)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-merge.c (ffffffff814fa8d5)
Location: block/blk-merge.c:701
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
```
</details>
</li>
</ul>

## Differences
