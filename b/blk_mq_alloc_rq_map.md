# Function: <code>blk_mq_alloc_rq_map</code>

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
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432610)
Location: block/blk-mq.c:1716
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81432610-ffffffff814326bf: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145e1e0)
Location: block/blk-mq.c:1850
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff8145e1e0-ffffffff8145e28f: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491b10)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81491b10-ffffffff81491bc9: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab580)
Location: block/blk-mq.c:2073
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814ab580-ffffffff814ab636: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9770)
Location: block/blk-mq.c:2072
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814d9770-ffffffff814d9827: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2b30)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814f2b30-ffffffff814f2be7: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815530f0)
Location: block/blk-mq.c:2201
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815530f0-ffffffff815531a7: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156f780)
Location: block/blk-mq.c:2302
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8156f780-ffffffff8156f83c: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81577630)
Location: block/blk-mq.c:2368
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81577630-ffffffff815776ec: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dc350)
Location: block/blk-mq.c:2391
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815dc350-ffffffff815dc40c: blk_mq_alloc_rq_map (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff8168a222)
Location: block/blk-mq.c:3147
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
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
In block/blk-mq.c (ffffffff81748812)
Location: block/blk-mq.c:3310
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
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
In block/blk-mq.c (ffffffff81784f22)
Location: block/blk-mq.c:3322
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
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
In block/blk-mq.c (ffffffff817c7432)
Location: block/blk-mq.c:3338
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
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
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2360)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffff8000105f2360-ffff8000105f243c: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079e460)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c079e460-c079e52c: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000789560)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c000000000789560-c00000000078967c: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430c68)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffe000430c68-ffffffe000430d16: blk_mq_alloc_rq_map (STB_GLOBAL)
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
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eb110)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814eb110-ffffffff814eb1c7: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db660)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814db660-ffffffff814db717: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e71a0)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814e71a0-ffffffff814e7257: blk_mq_alloc_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81500140)
Location: block/blk-mq.c:2098
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81500140-ffffffff815001f7: blk_mq_alloc_rq_map (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
