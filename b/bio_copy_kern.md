# Function: <code>bio_copy_kern</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b2a70)
Location: block/bio.c:1491
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff813b2a70-ffffffff813b2c44: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f6200)
Location: block/bio.c:1491
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff813f6200-ffffffff813f6408: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140fbf0)
Location: block/bio.c:1546
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff8140fbf0-ffffffff8140fde8: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d570)
Location: block/bio.c:1553
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff8141d570-ffffffff8141d764: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81448400)
Location: block/bio.c:1517
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff81448400-ffffffff814485f4: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147b550)
Location: block/bio.c:1572
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff8147b550-ffffffff8147b73e: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814996c0)
Location: block/bio.c:1498
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814996c0-ffffffff814998ae: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7820)
Location: block/bio.c:1557
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814c7820-ffffffff814c79ee: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e08f0)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814e08f0-ffffffff814e0ae6: bio_copy_kern (STB_GLOBAL)
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
In block/blk-map.c (ffffffff81549f61)
Location: block/blk-map.c:466
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
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
In block/blk-map.c (ffffffff81565d11)
Location: block/blk-map.c:463
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
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
In block/blk-map.c (ffffffff8156e28c)
Location: block/blk-map.c:421
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
In block/blk-map.c (ffffffff815d274c)
Location: block/blk-map.c:421
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
In block/blk-map.c (ffffffff8167e4aa)
Location: block/blk-map.c:427
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
In block/blk-map.c (ffffffff8173b18a)
Location: block/blk-map.c:468
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81777640)
Location: block/blk-map.c:467
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff81777640-ffffffff8177783b: bio_copy_kern (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817b9860)
Location: block/blk-map.c:474
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff817b9860-ffffffff817b9a5b: bio_copy_kern (STB_LOCAL)
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
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd450)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffff8000105dd450-ffff8000105dd5e8: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078a8b4)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
c078a8b4-c078aa30: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076ebc0)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
c00000000076ebc0-c00000000076ee48: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe000420582)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffe000420582-ffffffe0004206d8: bio_copy_kern (STB_GLOBAL)
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
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d8ed0)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814d8ed0-ffffffff814d90c6: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9880)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814c9880-ffffffff814c9a76: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d4f60)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814d4f60-ffffffff814d5156: bio_copy_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bio *bio_copy_kern(struct request_queue *q, void *data, unsigned int len, gfp_t gfp_mask, int reading);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814edb10)
Location: block/bio.c:1599
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff814edb10-ffffffff814edd06: bio_copy_kern (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
