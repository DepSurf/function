# Function: <code>blk_mq_sched_bio_merge</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8143136e)
Location: block/blk-mq-sched.h:38
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff8145cd5d)
Location: block/blk-mq-sched.h:39
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814905fe)
Location: block/blk-mq-sched.h:37
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814aaa1c)
Location: block/blk-mq-sched.h:33
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814d84d7)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814f1887)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff81550f6b)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff8156ee1b)
Location: block/blk-mq-sched.h:32
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-mq.c (ffffffff815769f3)
Location: block/blk-mq-sched.h:31
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-mq.c (ffffffff815db6a3)
Location: block/blk-mq-sched.h:34
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168f840)
Location: block/blk-mq-sched.c:345
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff8168f840-ffffffff8168f9f8: blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174e390)
Location: block/blk-mq-sched.c:344
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff8174e390-ffffffff8174e548: blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8178a8d0)
Location: block/blk-mq-sched.c:339
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff8178a8d0-ffffffff8178aa88: blk_mq_sched_bio_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_mq_sched_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff817cd020)
Location: block/blk-mq-sched.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_attempt_bio_merge
```
**Symbols:**

```
ffffffff817cd020-ffffffff817cd1d8: blk_mq_sched_bio_merge (STB_GLOBAL)
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
In block/blk-mq.c (ffff8000105f0f04)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (c079cf90)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (c000000000787bc4)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffe00042fbde)
Location: block/blk-mq-sched.h:35
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9e67)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814da3c7)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814e5ef7)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-mq.c (ffffffff814fee67)
Location: block/blk-mq-sched.h:35
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
