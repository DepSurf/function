# Function: <code>sbitmap_init_node</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814820a0)
Location: lib/sbitmap.c:21
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814820a0-ffffffff8148218b: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148b300)
Location: lib/sbitmap.c:23
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8148b300-ffffffff8148b3ed: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c7420)
Location: lib/sbitmap.c:23
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814c7420-ffffffff814c750d: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f8a20)
Location: lib/sbitmap.c:23
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814f8a20-ffffffff814f8b45: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150ce50)
Location: lib/sbitmap.c:57
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8150ce50-ffffffff8150cf8b: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153b550)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8153b550-ffffffff8153b68e: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155c360)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8155c360-ffffffff8155c49e: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e5c20)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff815e5c20-ffffffff815e5d5e: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81609fe0)
Location: lib/sbitmap.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff81609fe0-ffffffff8160a10e: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node, bool round_robin, bool alloc_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed070)
Location: lib/sbitmap.c:83
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff815ed070-ffffffff815ed274: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node, bool round_robin, bool alloc_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:83
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81cdedf3-ffffffff81cdee73: sbitmap_init_node.cold (STB_LOCAL)
ffffffff8165a040-ffffffff8165a26f: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node, bool round_robin, bool alloc_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:83
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81ea5250-ffffffff81ea52cb: sbitmap_init_node.cold (STB_LOCAL)
ffffffff817726a0-ffffffff81772885: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node, bool round_robin, bool alloc_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:83
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff8208da4a-ffffffff8208dac5: sbitmap_init_node.cold (STB_LOCAL)
ffffffff818a3a00-ffffffff818a3bec: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node, bool round_robin, bool alloc_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:83
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff8210dd68-ffffffff8210dde5: sbitmap_init_node.cold (STB_LOCAL)
ffffffff818e5ee0-ffffffff818e60c7: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node, bool round_robin, bool alloc_hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:83
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff821eb9a5-ffffffff821eba22: sbitmap_init_node.cold (STB_LOCAL)
ffffffff8192cee0-ffffffff8192d0c7: sbitmap_init_node (STB_GLOBAL)
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
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff800010669298)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffff800010669298-ffff8000106693e0: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c0811f28)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
c0811f28-c08120c4: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081f670)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
c00000000081f670-c00000000081f858: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe0004946b4)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffe0004946b4-ffffffe0004947d2: sbitmap_init_node (STB_GLOBAL)
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
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554950)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81554950-ffffffff81554a8e: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81544bd0)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81544bd0-ffffffff81544d0e: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81550690)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81550690-ffffffff815507ce: sbitmap_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sbitmap_init_node(struct sbitmap *sb, unsigned int depth, int shift, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a4d0)
Location: lib/sbitmap.c:44
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8156a4d0-ffffffff8156a60e: sbitmap_init_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool round_robin</code>
</li>
<li>
<b>Param added. </b>
<code>bool alloc_hint</code>
</li>
</ul>
</details>
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
