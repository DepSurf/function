# Function: <code>blk_mq_attempt_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_mq_attempt_merge(struct request_queue *q, struct blk_mq_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3270)
Location: block/blk-mq.c:648
Inline: False
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813c3270-ffffffff813c3317: blk_mq_attempt_merge (STB_LOCAL)
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
In block/blk-mq.c (ffffffff81409e75)
Location: block/blk-mq.c:725
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814247f9)
Location: block/blk-mq.c:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq-sched.c (ffffffff814358c9)
Location: block/blk-mq-sched.c:186
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff8146165f)
Location: block/blk-mq-sched.c:274
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff8149507a)
Location: block/blk-mq-sched.c:317
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff814af155)
Location: block/blk-mq-sched.c:304
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff814dd3ca)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff814f683a)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff815572e4)
Location: block/blk-mq-sched.c:372
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In block/blk-mq-sched.c (ffff8000105f6e68)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (c07a25f4)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (c00000000078f32c)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffe000434604)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff814eee1a)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff814df35a)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff814eaeaa)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq-sched.c (ffffffff81503e8a)
Location: block/blk-mq-sched.c:307
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
