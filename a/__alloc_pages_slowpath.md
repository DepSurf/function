# Function: <code>__alloc_pages_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81196882)
Location: mm/page_alloc.c:2970
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811aa5a0)
Location: mm/page_alloc.c:3402
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff811aa5a0-ffffffff811aaff4: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811baae0)
Location: mm/page_alloc.c:3519
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff811baae0-ffffffff811bb679: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c2b60)
Location: mm/page_alloc.c:3781
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff811c2b60-ffffffff811c3985: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d78d0)
Location: mm/page_alloc.c:3909
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff811d78d0-ffffffff811d8721: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f8b10)
Location: mm/page_alloc.c:4043
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff811f8b10-ffffffff811f98e4: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120b090)
Location: mm/page_alloc.c:4216
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff8120b090-ffffffff8120bf2e: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81271320)
Location: mm/page_alloc.c:4383
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81271320-ffffffff81272143: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81280160)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81280160-ffffffff81280fa4: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812b29c0)
Location: mm/page_alloc.c:4495
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812b29c0-ffffffff812b3499: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812be530)
Location: mm/page_alloc.c:4649
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812be530-ffffffff812bef46: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812c35c0)
Location: mm/page_alloc.c:4698
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff812c35c0-ffffffff812c3fcb: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81307440)
Location: mm/page_alloc.c:4874
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff81307440-ffffffff81307e76: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4906
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff8136f790-ffffffff81370138: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
ffffffff81e6f883-ffffffff81e6f8bf: __alloc_pages_slowpath.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5015
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff813ebdb0-ffffffff813ec7c9: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
ffffffff820655e0-ffffffff8206562c: __alloc_pages_slowpath.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3950
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff81420dc0-ffffffff81421739: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
ffffffff820e4dd9-ffffffff820e4e25: __alloc_pages_slowpath.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4040
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff8144db80-ffffffff8144e566: __alloc_pages_slowpath.constprop.0 (STB_LOCAL)
ffffffff821c1aa8-ffffffff821c1b04: __alloc_pages_slowpath.constprop.0.cold (STB_LOCAL)
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
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103180c8)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffff8000103180c8-ffff800010318c44: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c053262c)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
c053262c-c053363c: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ea710)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
c0000000003ea710-c0000000003eb5b4: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021df22)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffe00021df22-ffffffe00021ea0e: __alloc_pages_slowpath (STB_LOCAL)
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
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812787b0)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812787b0-ffffffff812795f4: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126a6a0)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff8126a6a0-ffffffff8126b4e4: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276550)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81276550-ffffffff81277394: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81286110)
Location: mm/page_alloc.c:4377
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81286110-ffffffff81286f81: __alloc_pages_slowpath (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
