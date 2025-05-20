# Function: <code>blk_mq_hw_queue_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(unsigned int *mq_map, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff813c87f0)
Location: block/blk-mq-cpumap.c:110
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff813c87f0-ffffffff813c885d: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(unsigned int *mq_map, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8140ca50)
Location: block/blk-mq-cpumap.c:110
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8140ca50-ffffffff8140cabd: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(unsigned int *mq_map, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81427d20)
Location: block/blk-mq-cpumap.c:96
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81427d20-ffffffff81427d92: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(unsigned int *mq_map, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81435110)
Location: block/blk-mq-cpumap.c:70
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81435110-ffffffff81435180: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(unsigned int *mq_map, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81460d10)
Location: block/blk-mq-cpumap.c:70
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81460d10-ffffffff81460d73: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(unsigned int *mq_map, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814945d0)
Location: block/blk-mq-cpumap.c:65
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814945d0-ffffffff81494633: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814ae700)
Location: block/blk-mq-cpumap.c:66
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814ae700-ffffffff814ae766: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814dc9c0)
Location: block/blk-mq-cpumap.c:71
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814dc9c0-ffffffff814dca1b: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814f5e30)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814f5e30-ffffffff814f5e8b: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81556850)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81556850-ffffffff815568ab: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff815730a0)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff815730a0-ffffffff815730fb: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8157b0e0)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff8157b0e0-ffffffff8157b145: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff815e0430)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff815e0430-ffffffff815e04b6: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8168ee70)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_get_hctx_node
```
**Symbols:**

```
ffffffff8168ee70-ffffffff8168ef06: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8174d920)
Location: block/blk-mq-cpumap.c:84
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8174d920-ffffffff8174d9b9: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81789ea0)
Location: block/blk-mq-cpumap.c:46
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81789ea0-ffffffff81789f39: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff817cc620)
Location: block/blk-mq-cpumap.c:46
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff817cc620-ffffffff817cc6b9: blk_mq_hw_queue_to_node (STB_GLOBAL)
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
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffff8000105f61c0)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffff8000105f61c0-ffff8000105f625c: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (c07a1af4)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
c07a1af4-c07a1b5c: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (c00000000078e2f0)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
c00000000078e2f0-c00000000078e3e4: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffe000433d08)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffe000433d08-ffffffe000433d86: blk_mq_hw_queue_to_node (STB_GLOBAL)
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
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814ee410)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814ee410-ffffffff814ee46b: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814de960)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814de960-ffffffff814de9bb: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff814ea4a0)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814ea4a0-ffffffff814ea4fb: blk_mq_hw_queue_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_mq_hw_queue_to_node(struct blk_mq_queue_map *qmap, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81503470)
Location: block/blk-mq-cpumap.c:86
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81503470-ffffffff815034cb: blk_mq_hw_queue_to_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_queue_map *qmap</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *mq_map</code>
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
