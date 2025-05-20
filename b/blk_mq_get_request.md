# Function: <code>blk_mq_get_request</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, unsigned int op, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f0d0)
Location: block/blk-mq.c:297
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff8142f0d0-ffffffff8142f458: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, unsigned int op, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a610)
Location: block/blk-mq.c:331
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff8145a610-ffffffff8145a9ad: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, unsigned int op, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148eb70)
Location: block/blk-mq.c:339
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff8148eb70-ffffffff8148ef39: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8580)
Location: block/blk-mq.c:350
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814a8580-ffffffff814a89bb: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5fc0)
Location: block/blk-mq.c:351
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814d5fc0-ffffffff814d639b: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ef2f0)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814ef2f0-ffffffff814ef701: blk_mq_get_request (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ef798)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffff8000105ef798-ffff8000105efb44: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a85c)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
c079a85c-c079ac48: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000784590)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
c000000000784590-c000000000784a6c: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d8b8)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffe00042d8b8-ffffffe00042dbde: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e78d0)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814e78d0-ffffffff814e7ce1: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7e40)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814d7e40-ffffffff814d8251: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3960)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814e3960-ffffffff814e3d71: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *blk_mq_get_request(struct request_queue *q, struct bio *bio, struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fceb0)
Location: block/blk-mq.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814fceb0-ffffffff814fd2df: blk_mq_get_request (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bio, op, data</code> ➡️ <code>q, bio, data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
