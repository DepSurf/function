# Function: <code>blk_mq_alloc_rqs</code>

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
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814326c0)
Location: block/blk-mq.c:1758
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff814326c0-ffffffff8143291d: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145e290)
Location: block/blk-mq.c:1892
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff8145e290-ffffffff8145e4f0: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491bd0)
Location: block/blk-mq.c:1964
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81491bd0-ffffffff81491e15: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab640)
Location: block/blk-mq.c:2130
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814ab640-ffffffff814ab882: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9830)
Location: block/blk-mq.c:2129
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814d9830-ffffffff814d9a80: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2bf0)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814f2bf0-ffffffff814f2e40: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815531b0)
Location: block/blk-mq.c:2258
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815531b0-ffffffff81553420: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156f840)
Location: block/blk-mq.c:2359
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8156f840-ffffffff8156fab0: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815776f0)
Location: block/blk-mq.c:2420
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815776f0-ffffffff81577968: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dc410)
Location: block/blk-mq.c:2443
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815dc410-ffffffff815dc683: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81689d60)
Location: block/blk-mq.c:3198
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff81689d60-ffffffff81689ff4: blk_mq_alloc_rqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817482e0)
Location: block/blk-mq.c:3362
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff817482e0-ffffffff81748577: blk_mq_alloc_rqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817849f0)
Location: block/blk-mq.c:3374
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff817849f0-ffffffff81784c83: blk_mq_alloc_rqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c6f00)
Location: block/blk-mq.c:3390
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff817c6f00-ffffffff817c7193: blk_mq_alloc_rqs (STB_LOCAL)
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2440)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffff8000105f2440-ffff8000105f2670: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079e52c)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c079e52c-c079e76c: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000789680)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c000000000789680-c0000000007899b8: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430d16)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffe000430d16-ffffffe000430f00: blk_mq_alloc_rqs (STB_GLOBAL)
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eb1d0)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814eb1d0-ffffffff814eb420: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db720)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814db720-ffffffff814db970: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7260)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814e7260-ffffffff814e74b0: blk_mq_alloc_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81500200)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81500200-ffffffff81500450: blk_mq_alloc_rqs (STB_GLOBAL)
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
