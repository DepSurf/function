# Function: <code>blk_mq_sched_bypass_insert</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435d5c)
Location: block/blk-mq-sched.c:262
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814353f0-ffffffff81435434: blk_mq_sched_bypass_insert.part.7 (STB_LOCAL)
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
In block/blk-mq-sched.c (ffffffff81461979)
Location: block/blk-mq-sched.c:350
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff814952dd)
Location: block/blk-mq-sched.c:366
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814af25d)
Location: block/blk-mq-sched.c:358
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff814dd985)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff814f696f)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff8155741b)
Location: block/blk-mq-sched.c:425
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff81573a03)
Location: block/blk-mq-sched.c:393
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff8157ba9c)
Location: block/blk-mq-sched.c:399
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff815e0e87)
Location: block/blk-mq-sched.c:409
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff8168fa48)
Location: block/blk-mq-sched.c:388
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff8174e5a8)
Location: block/blk-mq-sched.c:387
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6f60)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (c07a26c4)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (c00000000078f508)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffe0004346b6)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff814eef4f)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff814df48f)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff814eafdf)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
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
In block/blk-mq-sched.c (ffffffff81503fb0)
Location: block/blk-mq-sched.c:360
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
</details>
</li>
</ul>

## Differences
