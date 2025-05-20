# Function: <code>bio_add_pc_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0990)
Location: block/bio.c:711
Inline: True
Direct callers:
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_kern
```
**Symbols:**

```
ffffffff813b0990-ffffffff813b0b61: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4380)
Location: block/bio.c:714
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff813f4380-ffffffff813f4557: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140dd70)
Location: block/bio.c:719
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8140dd70-ffffffff8140df47: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b9d0)
Location: block/bio.c:735
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8141b9d0-ffffffff8141bb9c: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446690)
Location: block/bio.c:738
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81446690-ffffffff8144685c: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479500)
Location: block/bio.c:739
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81479500-ffffffff814796c9: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814974f0)
Location: block/bio.c:665
Inline: True
Direct callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814974f0-ffffffff814976d2: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c78bd)
Location: block/bio.c:743
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814c5080-ffffffff814c5093: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e09ae)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814ddf60-ffffffff814ddf9f: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f630)
Location: block/bio.c:845
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8153f630-ffffffff8153f677: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155be40)
Location: block/bio.c:845
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8155be40-ffffffff8155be87: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81564490)
Location: block/bio.c:801
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81564490-ffffffff815644d7: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c8920)
Location: block/bio.c:884
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff815c8920-ffffffff815c8967: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816737e0)
Location: block/bio.c:1002
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff816737e0-ffffffff81673835: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172f3b0)
Location: block/bio.c:1057
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8172f3b0-ffffffff8172f405: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176b660)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8176b660-ffffffff8176b6b5: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817adb00)
Location: block/bio.c:1020
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff817adb00-ffffffff817adb55: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd540)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffff8000105da590-ffff8000105da618: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c078a988)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
c0788288-c07882f4: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076ed04)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
c00000000076b430-c00000000076b494: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe000420620)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffe00041e2ba-ffffffe00041e30c: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d8f8e)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814d6540-ffffffff814d657f: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c993e)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814c6ea0-ffffffff814c6edf: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d501e)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814d25d0-ffffffff814d260f: bio_add_pc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bio_add_pc_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814edbce)
Location: block/bio.c:776
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_map_kern
  - block/bio.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff814eb0f0-ffffffff814eb12f: bio_add_pc_page (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
