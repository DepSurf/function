# Function: <code>get_page_from_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81195c80)
Location: mm/page_alloc.c:2480
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81195c80-ffffffff811966cc: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9690)
Location: mm/page_alloc.c:2844
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811a9690-ffffffff811aa1dd: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b9bf0)
Location: mm/page_alloc.c:2895
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811b9bf0-ffffffff811ba708: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1c20)
Location: mm/page_alloc.c:3078
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811c1c20-ffffffff811c2731: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d6150)
Location: mm/page_alloc.c:3146
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811d6150-ffffffff811d754f: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f7580)
Location: mm/page_alloc.c:3250
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811f7580-ffffffff811f8892: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812099a0)
Location: mm/page_alloc.c:3397
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff812099a0-ffffffff8120addb: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270ca0)
Location: mm/page_alloc.c:3565
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81270ca0-ffffffff8127102e: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127fae0)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8127fae0-ffffffff8127fe6c: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b2190)
Location: mm/page_alloc.c:3671
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812b2190-ffffffff812b2446: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bdb60)
Location: mm/page_alloc.c:3821
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812bdb60-ffffffff812bdf29: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c2da0)
Location: mm/page_alloc.c:3868
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812c2da0-ffffffff812c3251: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4039
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81306a70-ffffffff81306f81: get_page_from_freelist (STB_LOCAL)
ffffffff81cbd8eb-ffffffff81cbd976: get_page_from_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4081
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
```
**Symbols:**

```
ffffffff8136ec20-ffffffff8136f093: get_page_from_freelist (STB_LOCAL)
ffffffff81e6f80d-ffffffff81e6f821: get_page_from_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4166
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
```
**Symbols:**

```
ffffffff813eb150-ffffffff813eb5fa: get_page_from_freelist (STB_LOCAL)
ffffffff820655b7-ffffffff820655cb: get_page_from_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3099
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
```
**Symbols:**

```
ffffffff814200c0-ffffffff81420620: get_page_from_freelist (STB_LOCAL)
ffffffff820e4daf-ffffffff820e4dc4: get_page_from_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3170
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__alloc_pages_may_oom
```
**Symbols:**

```
ffffffff8144cd10-ffffffff8144d3e0: get_page_from_freelist (STB_LOCAL)
ffffffff821c1a7e-ffffffff821c1a93: get_page_from_freelist.cold (STB_LOCAL)
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
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317868)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffff800010317868-ffff800010317c50: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531cdc)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
c0531cdc-c0531fa4: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e9d20)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
c0000000003e9d20-c0000000003ea164: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d7c0)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffe00021d7c0-ffffffe00021d9e0: get_page_from_freelist (STB_LOCAL)
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
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278130)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81278130-ffffffff812784bc: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126a020)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8126a020-ffffffff8126a3ac: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275ed0)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81275ed0-ffffffff8127625c: get_page_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *get_page_from_freelist(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285ab0)
Location: mm/page_alloc.c:3556
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81285ab0-ffffffff81285e3c: get_page_from_freelist (STB_LOCAL)
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
