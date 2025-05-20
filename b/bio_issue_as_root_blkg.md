# Function: <code>bio_issue_as_root_blkg</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
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
In block/blk-iocost.c (ffffffff81574b20)
Location: include/linux/blk-cgroup.h:309
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-iocost.c (ffffffff815917e9)
Location: include/linux/blk-cgroup.h:299
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-iocost.c (ffffffff81598639)
Location: include/linux/blk-cgroup.h:299
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-iocost.c (ffffffff815ffdfe)
Location: include/linux/blk-cgroup.h:304
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-merge.c (ffffffff81681261)
Location: block/blk-cgroup.h:224
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-iocost.c (ffffffff816b2543)
Location: block/blk-cgroup.h:224
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-merge.c (ffffffff8173e7bd)
Location: block/blk-cgroup.h:232
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-iocost.c (ffffffff81771a88)
Location: block/blk-cgroup.h:232
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-merge.c (ffffffff8177ad1d)
Location: block/blk-cgroup.h:233
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-iocost.c (ffffffff817b0d53)
Location: block/blk-cgroup.h:233
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-merge.c (ffffffff817bd0fe)
Location: block/blk-cgroup.h:233
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/blk-iocost.c (ffffffff817f4b63)
Location: block/blk-cgroup.h:233
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
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
In block/blk-iocost.c (c07c2ff0)
Location: include/linux/blk-cgroup.h:331
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
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
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
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
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
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
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
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
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
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
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
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
In block/blk-iocost.c (0)
Location: include/linux/blk-cgroup.h:331
Inline: True
```
</details>
</li>
</ul>

## Differences
