# Function: <code>bio_map_kern</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b2930)
Location: block/bio.c:1419
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/block/virtio_blk.c:virtblk_serial_show
```
**Symbols:**

```
ffffffff813b2930-ffffffff813b2a59: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f60c0)
Location: block/bio.c:1419
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - drivers/lightnvm/core.c:__nvm_submit_ppa
```
**Symbols:**

```
ffffffff813f60c0-ffffffff813f61f0: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140fac0)
Location: block/bio.c:1474
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - drivers/lightnvm/core.c:__nvm_submit_ppa
```
**Symbols:**

```
ffffffff8140fac0-ffffffff8140fbdd: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d440)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff8141d440-ffffffff8141d55d: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814482d0)
Location: block/bio.c:1445
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814482d0-ffffffff814483ed: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147b420)
Location: block/bio.c:1500
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff8147b420-ffffffff8147b53d: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498b80)
Location: block/bio.c:1426
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff81498b80-ffffffff81498c9d: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6b60)
Location: block/bio.c:1474
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814c6b60-ffffffff814c6cf3: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e0730)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814e0730-ffffffff814e08eb: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81549b50)
Location: block/blk-map.c:384
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff81549b50-ffffffff81549cb7: bio_map_kern (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81565ab0)
Location: block/blk-map.c:381
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff81565ab0-ffffffff81565c17: bio_map_kern (STB_LOCAL)
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
In block/blk-map.c (ffffffff8156e16d)
Location: block/blk-map.c:339
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
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
In block/blk-map.c (ffffffff815d262d)
Location: block/blk-map.c:339
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
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
In block/blk-map.c (ffffffff8167e362)
Location: block/blk-map.c:342
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
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
In block/blk-map.c (ffffffff8173b042)
Location: block/blk-map.c:383
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
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
In block/blk-map.c (ffffffff81777954)
Location: block/blk-map.c:382
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
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
In block/blk-map.c (ffffffff817b9b74)
Location: block/blk-map.c:389
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd290)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffff8000105dd290-ffff8000105dd450: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078a6e8)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
c078a6e8-c078a8b4: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076e960)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
c00000000076e960-c00000000076ebbc: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00042043c)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffe00042043c-ffffffe000420582: bio_map_kern (STB_GLOBAL)
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
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d8d10)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814d8d10-ffffffff814d8ecb: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c96c0)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814c96c0-ffffffff814c987b: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d4da0)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814d4da0-ffffffff814d4f5b: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bio *bio_map_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ed950)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814ed950-ffffffff814edb0b: bio_map_kern (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
