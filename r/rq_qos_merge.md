# Function: <code>rq_qos_merge</code>

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
In block/blk-core.c (ffffffff814e6e0e)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (ffffffff81545bcf)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-core.c:bio_attempt_front_merge
  - block/blk-core.c:bio_attempt_back_merge
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
In block/blk-merge.c (ffffffff81567811)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
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
In block/blk-merge.c (ffffffff8156fea1)
Location: block/blk-rq-qos.h:216
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
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
In block/blk-merge.c (ffffffff815d4540)
Location: block/blk-rq-qos.h:204
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
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
In block/blk-merge.c (ffffffff81680385)
Location: block/blk-rq-qos.h:219
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:bio_attempt_back_merge
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
In block/blk-merge.c (ffffffff8173d70d)
Location: block/blk-rq-qos.h:218
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:bio_attempt_back_merge
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
In block/blk-merge.c (ffffffff81779c8d)
Location: block/blk-rq-qos.h:162
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:bio_attempt_back_merge
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
In block/blk-merge.c (ffffffff817bc05d)
Location: block/blk-rq-qos.h:162
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:bio_attempt_back_merge
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
In block/blk-core.c (ffff8000105e4760)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (c079199c)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (c0000000007785b4)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (ffffffe000425e9c)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (ffffffff814df3ee)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (ffffffff814cfd8e)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (ffffffff814db47e)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
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
In block/blk-core.c (ffffffff814f42ee)
Location: block/blk-rq-qos.h:192
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
</details>
</li>
</ul>

## Differences
