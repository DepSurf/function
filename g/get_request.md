# Function: <code>get_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request *get_request(struct request_queue *q, int rw_flags, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b8da0)
Location: block/blk-core.c:1232
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813b8da0-ffffffff813b952d: get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request *get_request(struct request_queue *q, int op, int op_flags, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fcb90)
Location: block/blk-core.c:1245
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff813fcb90-ffffffff813fd395: get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request *get_request(struct request_queue *q, unsigned int op, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416530)
Location: block/blk-core.c:1247
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff81416530-ffffffff81416cf6: get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *get_request(struct request_queue *q, unsigned int op, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423c20)
Location: block/blk-core.c:1342
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff81423c20-ffffffff814243f1: get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *get_request(struct request_queue *q, unsigned int op, struct bio *bio, blk_mq_req_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144f3a0)
Location: block/blk-core.c:1424
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_get_request_flags
```
**Symbols:**

```
ffffffff8144f3a0-ffffffff8144fb95: get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct request *get_request(struct request_queue *q, unsigned int op, struct bio *bio, blk_mq_req_flags_t flags, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1529
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff81481d90-ffffffff81482558: get_request (STB_LOCAL)
ffffffff81485708-ffffffff81485745: get_request.cold.99 (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, rw_flags, bio, gfp_mask</code> ➡️ <code>q, op, op_flags, bio, gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, op, op_flags, bio, gfp_mask</code> ➡️ <code>q, op, bio, gfp_mask</code>
</li>
<li>
<b>Param type changed. </b>
<code>int op</code> ➡️ <code>unsigned int op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_mq_req_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
</ul>
