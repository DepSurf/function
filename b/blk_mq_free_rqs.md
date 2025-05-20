# Function: <code>blk_mq_free_rqs</code>

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
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432040)
Location: block/blk-mq.c:1676
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81432040-ffffffff81432104: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145db70)
Location: block/blk-mq.c:1810
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff8145db70-ffffffff8145dc3a: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491460)
Location: block/blk-mq.c:1867
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81491460-ffffffff8149152a: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aaf10)
Location: block/blk-mq.c:2033
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff814aaf10-ffffffff814aafda: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9050)
Location: block/blk-mq.c:2032
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814d9050-ffffffff814d911a: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2410)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814f2410-ffffffff814f24da: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81552ca0)
Location: block/blk-mq.c:2161
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81552ca0-ffffffff81552d6a: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156f2d0)
Location: block/blk-mq.c:2262
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8156f2d0-ffffffff8156f39a: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81576ec0)
Location: block/blk-mq.c:2326
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81576ec0-ffffffff8157704e: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2349
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81cd854c-ffffffff81cd857c: blk_mq_free_rqs.cold (STB_LOCAL)
ffffffff815dbbf0-ffffffff815dbda2: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3069
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
```
**Symbols:**

```
ffffffff81e8bcbb-ffffffff81e8bce9: blk_mq_free_rqs.cold (STB_LOCAL)
ffffffff81689b80-ffffffff81689d60: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3232
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
```
**Symbols:**

```
ffffffff820762fd-ffffffff8207632b: blk_mq_free_rqs.cold (STB_LOCAL)
ffffffff817480e0-ffffffff817482c9: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3244
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
```
**Symbols:**

```
ffffffff820f618b-ffffffff820f61b9: blk_mq_free_rqs.cold (STB_LOCAL)
ffffffff817847f0-ffffffff817849d7: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3260
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
```
**Symbols:**

```
ffffffff821d36b0-ffffffff821d36de: blk_mq_free_rqs.cold (STB_LOCAL)
ffffffff817c6d00-ffffffff817c6ee7: blk_mq_free_rqs (STB_GLOBAL)
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
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f1c88)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffff8000105f1c88-ffff8000105f1d68: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079dd74)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c079dd74-c079de50: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788bf0)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c000000000788bf0-c000000000788d38: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430660)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffe000430660-ffffffe000430702: blk_mq_free_rqs (STB_GLOBAL)
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
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ea9f0)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814ea9f0-ffffffff814eaaba: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814daf40)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814daf40-ffffffff814db00a: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6a80)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814e6a80-ffffffff814e6b4a: blk_mq_free_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ffa30)
Location: block/blk-mq.c:2058
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_map_and_requests
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-sched.c:blk_mq_sched_free_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814ffa30-ffffffff814ffafa: blk_mq_free_rqs (STB_GLOBAL)
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
