# Function: <code>__alloc_pages_direct_compact</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac, enum migrate_mode mode, int *contended_compaction, bool *deferred_compaction);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811966d0)
Location: mm/page_alloc.c:2753
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff811966d0-ffffffff811967c0: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811aa1e0)
Location: mm/page_alloc.c:3095
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811aa1e0-ffffffff811aa2c3: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ba710)
Location: mm/page_alloc.c:3142
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811ba710-ffffffff811ba7f3: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c2740)
Location: mm/page_alloc.c:3363
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811c2740-ffffffff811c2836: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d7550)
Location: mm/page_alloc.c:3425
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811d7550-ffffffff811d7646: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f88a0)
Location: mm/page_alloc.c:3547
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811f88a0-ffffffff811f8996: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120ade0)
Location: mm/page_alloc.c:3709
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8120ade0-ffffffff8120af1c: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81271030)
Location: mm/page_alloc.c:3877
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81271030-ffffffff812711a4: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127fe70)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8127fe70-ffffffff8127ffe4: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b2450)
Location: mm/page_alloc.c:3978
Inline: False
```
**Symbols:**

```
ffffffff812b2450-ffffffff812b25bb: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bdf30)
Location: mm/page_alloc.c:4127
Inline: False
```
**Symbols:**

```
ffffffff812bdf30-ffffffff812be113: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c3260)
Location: mm/page_alloc.c:4174
Inline: False
```
**Symbols:**

```
ffffffff812c3260-ffffffff812c3443: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4347
Inline: False
```
**Symbols:**

```
ffffffff81306f90-ffffffff813071b7: __alloc_pages_direct_compact (STB_LOCAL)
ffffffff81cbd976-ffffffff81cbd9c7: __alloc_pages_direct_compact.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136f0a0)
Location: mm/page_alloc.c:4391
Inline: False
```
**Symbols:**

```
ffffffff8136f0a0-ffffffff8136f2da: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813eb610)
Location: mm/page_alloc.c:4476
Inline: False
```
**Symbols:**

```
ffffffff813eb610-ffffffff813eb84a: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81420630)
Location: mm/page_alloc.c:3419
Inline: False
```
**Symbols:**

```
ffffffff81420630-ffffffff8142086a: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144d3f0)
Location: mm/page_alloc.c:3509
Inline: False
```
**Symbols:**

```
ffffffff8144d3f0-ffffffff8144d62a: __alloc_pages_direct_compact (STB_LOCAL)
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
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317c50)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffff800010317c50-ffff800010317e1c: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531fa4)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c0531fa4-c0532180: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ea170)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c0000000003ea170-c0000000003ea3d0: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d9e0)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffe00021d9e0-ffffffe00021db74: __alloc_pages_direct_compact (STB_LOCAL)
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
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812784c0)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff812784c0-ffffffff81278634: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126a3b0)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8126a3b0-ffffffff8126a524: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276260)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81276260-ffffffff812763d4: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__alloc_pages_direct_compact(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, enum compact_result *compact_result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285e40)
Location: mm/page_alloc.c:3863
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81285e40-ffffffff81285f9f: __alloc_pages_direct_compact (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum compact_priority prio</code>
</li>
<li>
<b>Param added. </b>
<code>enum compact_result *compact_result</code>
</li>
<li>
<b>Param removed. </b>
<code>enum migrate_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>int *contended_compaction</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *deferred_compaction</code>
</li>
<li>
<b>Param type changed. </b>
<code>int alloc_flags</code> ➡️ <code>unsigned int alloc_flags</code>
</li>
</ul>
</details>
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
