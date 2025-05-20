# Function: <code>blk_mq_free_rq_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff813c39d0)
Location: block/blk-mq.c:1416
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_init_rq_map
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff813c39d0-ffffffff813c3a9c: blk_mq_free_rq_map.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81407500)
Location: block/blk-mq.c:1482
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_rq_map
```
**Symbols:**

```
ffffffff81407500-ffffffff814075d0: blk_mq_free_rq_map.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81421b80)
Location: block/blk-mq.c:1544
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_rq_map
```
**Symbols:**

```
ffffffff81421b80-ffffffff81421c68: blk_mq_free_rq_map.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432110)
Location: block/blk-mq.c:1706
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81432110-ffffffff81432156: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145dc40)
Location: block/blk-mq.c:1840
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff8145dc40-ffffffff8145dc86: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491530)
Location: block/blk-mq.c:1897
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81491530-ffffffff81491576: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aafe0)
Location: block/blk-mq.c:2063
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff814aafe0-ffffffff814ab026: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9120)
Location: block/blk-mq.c:2062
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814d9120-ffffffff814d916b: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f24e0)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814f24e0-ffffffff814f252b: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81553005)
Location: block/blk-mq.c:2191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815530a0-ffffffff815530ed: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156f665)
Location: block/blk-mq.c:2292
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8156f720-ffffffff8156f775: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81577515)
Location: block/blk-mq.c:2358
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815775d0-ffffffff81577625: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dbdf5)
Location: block/blk-mq.c:2381
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_map_and_request
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815dc2f0-ffffffff815dc345: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168a0e1)
Location: block/blk-mq.c:3110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff8168a1b0-ffffffff8168a1ff: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81748681)
Location: block/blk-mq.c:3273
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff81748790-ffffffff817487df: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81784d91)
Location: block/blk-mq.c:3285
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff81784ea0-ffffffff81784eef: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c72a1)
Location: block/blk-mq.c:3301
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff817c73b0-ffffffff817c73ff: blk_mq_free_rq_map (STB_GLOBAL)
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
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f1d68)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffff8000105f1d68-ffff8000105f1dac: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079de50)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
c079de50-c079de90: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788d40)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
c000000000788d40-c000000000788db0: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430702)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffe000430702-ffffffe000430748: blk_mq_free_rq_map (STB_GLOBAL)
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
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eaac0)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814eaac0-ffffffff814eab0b: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db010)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814db010-ffffffff814db05b: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6b50)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814e6b50-ffffffff814e6b9b: blk_mq_free_rq_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_free_rq_map(struct blk_mq_tags *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ffb00)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:__blk_mq_alloc_rq_map
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814ffb00-ffffffff814ffb4b: blk_mq_free_rq_map (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
