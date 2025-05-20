# Function: <code>blk_mq_get_hctx_type</code>

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
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (0)
Location: block/blk-mq.h:89
Inline: True
```
```
In block/blk-mq.c (ffffffff816897fb)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8168ca97)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8168f8b7)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:89
Inline: True
```
```
In block/blk-mq.c (ffffffff81747d77)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8174b287)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8174e407)
Location: block/blk-mq.h:89
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:85
Inline: True
```
```
In block/blk-mq.c (ffffffff81784378)
Location: block/blk-mq.h:85
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff817879a7)
Location: block/blk-mq.h:85
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8178a947)
Location: block/blk-mq.h:85
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:85
Inline: True
```
```
In block/blk-mq.c (ffffffff817c68f4)
Location: block/blk-mq.h:85
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff817ca077)
Location: block/blk-mq.h:85
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff817cd097)
Location: block/blk-mq.h:85
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
