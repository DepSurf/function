# Function: <code>blk_mq_rq_ctx_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c2e24)
Location: block/blk-mq.c:161
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
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
In block/blk-mq.c (ffffffff81406a18)
Location: block/blk-mq.c:161
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
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
In block/blk-mq.c (ffffffff81420e2a)
Location: block/blk-mq.c:170
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
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
In block/blk-mq.c (ffffffff8142f1b2)
Location: block/blk-mq.c:238
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff8145a6f3)
Location: block/blk-mq.c:270
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff8148ec48)
Location: block/blk-mq.c:277
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814a86ab)
Location: block/blk-mq.c:290
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814d608c)
Location: block/blk-mq.c:293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814ef3d0)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *blk_mq_rq_ctx_init(struct blk_mq_alloc_data *data, unsigned int tag, u64 alloc_time_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e360)
Location: block/blk-mq.c:273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
**Symbols:**

```
ffffffff8154e360-ffffffff8154e60f: blk_mq_rq_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *blk_mq_rq_ctx_init(struct blk_mq_alloc_data *data, unsigned int tag, u64 alloc_time_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156a790)
Location: block/blk-mq.c:277
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
**Symbols:**

```
ffffffff8156a790-ffffffff8156a9cf: blk_mq_rq_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *blk_mq_rq_ctx_init(struct blk_mq_alloc_data *data, unsigned int tag, u64 alloc_time_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815726d0)
Location: block/blk-mq.c:277
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
**Symbols:**

```
ffffffff815726d0-ffffffff815728fd: blk_mq_rq_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request *blk_mq_rq_ctx_init(struct blk_mq_alloc_data *data, unsigned int tag, u64 alloc_time_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d6d00)
Location: block/blk-mq.c:284
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
```
**Symbols:**

```
ffffffff815d6d00-ffffffff815d6f2d: blk_mq_rq_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81683760)
Location: block/blk-mq.c:341
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
**Symbols:**

```
ffffffff81683760-ffffffff816838f0: blk_mq_rq_ctx_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81740e90)
Location: block/blk-mq.c:372
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
**Symbols:**

```
ffffffff81740e90-ffffffff81741020: blk_mq_rq_ctx_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff8177d100)
Location: block/blk-mq.c:347
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
```
**Symbols:**

```
ffffffff8177d100-ffffffff8177d23d: blk_mq_rq_ctx_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff817bf490)
Location: block/blk-mq.c:347
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
**Symbols:**

```
ffffffff817bf490-ffffffff817bf5ca: blk_mq_rq_ctx_init.isra.0 (STB_LOCAL)
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
In block/blk-mq.c (ffff8000105ef8a0)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (c079a970)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (c0000000007846d8)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffe00042d9ae)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814e79b0)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814d7f20)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814e3a40)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814fcfa4)
Location: block/blk-mq.c:294
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
