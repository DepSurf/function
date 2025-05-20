# Function: <code>sbitmap_queue_init_node</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81482550)
Location: lib/sbitmap.c:199
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff81482550-ffffffff814826f5: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148bcb0)
Location: lib/sbitmap.c:289
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8148bcb0-ffffffff8148be5b: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c7db0)
Location: lib/sbitmap.c:289
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff814c7db0-ffffffff814c7f47: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f8b50)
Location: lib/sbitmap.c:304
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff814f8b50-ffffffff814f8ced: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150cf90)
Location: lib/sbitmap.c:382
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8150cf90-ffffffff8150d14b: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153b690)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8153b690-ffffffff8153b841: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155c4a0)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8155c4a0-ffffffff8155c651: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (ffffffff815e5d60)
Location: lib/sbitmap.c:352
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff815e5d60-ffffffff815e5f0c: sbitmap_queue_init_node.part.0 (STB_LOCAL)
ffffffff815e5f10-ffffffff815e5f59: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (ffffffff8160a110)
Location: lib/sbitmap.c:347
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
```
**Symbols:**

```
ffffffff8160a110-ffffffff8160a2bc: sbitmap_queue_init_node.part.0 (STB_LOCAL)
ffffffff8160a2c0-ffffffff8160a309: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed420)
Location: lib/sbitmap.c:429
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
```
**Symbols:**

```
ffffffff815ed420-ffffffff815ed56d: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8165a270)
Location: lib/sbitmap.c:429
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
**Symbols:**

```
ffffffff8165a270-ffffffff8165a3c9: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81772a50)
Location: lib/sbitmap.c:422
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
**Symbols:**

```
ffffffff81772a50-ffffffff81772bb9: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818a3c00)
Location: lib/sbitmap.c:422
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
**Symbols:**

```
ffffffff818a3c00-ffffffff818a3d61: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818e60e0)
Location: lib/sbitmap.c:415
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
**Symbols:**

```
ffffffff818e60e0-ffffffff818e6241: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8192d0e0)
Location: lib/sbitmap.c:410
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
**Symbols:**

```
ffffffff8192d0e0-ffffffff8192d261: sbitmap_queue_init_node (STB_GLOBAL)
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
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff8000106693e0)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffff8000106693e0-ffff8000106695e4: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c08120c4)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
c08120c4-c08122b8: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081f860)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
c00000000081f860-c00000000081faf8: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe0004947d2)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffe0004947d2-ffffffe000494994: sbitmap_queue_init_node (STB_GLOBAL)
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
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554a90)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff81554a90-ffffffff81554c41: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81544d10)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff81544d10-ffffffff81544ec1: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815507d0)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff815507d0-ffffffff81550981: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sbitmap_queue_init_node(struct sbitmap_queue *sbq, unsigned int depth, int shift, bool round_robin, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a610)
Location: lib/sbitmap.c:369
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8156a610-ffffffff8156a7c1: sbitmap_queue_init_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
