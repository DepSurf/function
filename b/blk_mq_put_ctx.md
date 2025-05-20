# Function: <code>blk_mq_put_ctx</code>

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
In block/blk-mq.c (ffffffff813c4b27)
Location: block/blk-mq.h:91
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-mq-tag.c (ffffffff813c72bc)
Location: block/blk-mq.h:91
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_get
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
In block/blk-mq.c (ffffffff81409c83)
Location: block/blk-mq.h:92
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff8140b4ec)
Location: block/blk-mq.h:92
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_get
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
In block/blk-mq.c (ffffffff814246d0)
Location: block/blk-mq.h:81
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-mq-tag.c (ffffffff81425b32)
Location: block/blk-mq.h:81
Inline: True
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
In block/blk-mq.c (ffffffff81431686)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81433b8b)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81435895)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq.c (ffffffff8145d04c)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff8145f84b)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81461625)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq.c (ffffffff8149086b)
Location: block/blk-mq.h:118
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814930e3)
Location: block/blk-mq.h:118
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8149503e)
Location: block/blk-mq.h:118
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-mq.c (ffffffff814aab18)
Location: block/blk-mq.h:159
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ad027)
Location: block/blk-mq.h:159
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814af0fb)
Location: block/blk-mq.h:159
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
</details>
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
