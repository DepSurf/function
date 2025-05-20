# Function: <code>blk_mq_get_new_requests</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request *blk_mq_get_new_requests(struct request_queue *q, struct blk_plug *plug, struct bio *bio, unsigned int nsegs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684110)
Location: block/blk-mq.c:2716
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81684110-ffffffff81684299: blk_mq_get_new_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *blk_mq_get_new_requests(struct request_queue *q, struct blk_plug *plug, struct bio *bio, unsigned int nsegs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817418f0)
Location: block/blk-mq.c:2859
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff817418f0-ffffffff81741a79: blk_mq_get_new_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request *blk_mq_get_new_requests(struct request_queue *q, struct blk_plug *plug, struct bio *bio, unsigned int nsegs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81781e10)
Location: block/blk-mq.c:2865
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81781e10-ffffffff81781f99: blk_mq_get_new_requests (STB_LOCAL)
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
In block/blk-mq.c (ffffffff817c6694)
Location: block/blk-mq.c:2882
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
