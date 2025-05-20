# Function: <code>should_fail_alloc_page</code>

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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2340
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2700
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2751
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2934
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2991
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3095
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81206620)
Location: mm/page_alloc.c:3209
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81206620-ffffffff8120662d: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126c5d0)
Location: mm/page_alloc.c:3374
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff8126c5d0-ffffffff8126c5dd: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127b3e0)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff8127b3e0-ffffffff8127b3ed: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ad580)
Location: mm/page_alloc.c:3476
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812ad580-ffffffff812ad58d: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b8f60)
Location: mm/page_alloc.c:3591
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812b8f60-ffffffff812b8f6d: should_fail_alloc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812be430)
Location: mm/page_alloc.c:3641
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff812be430-ffffffff812be43d: should_fail_alloc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81300b70)
Location: mm/page_alloc.c:3812
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff81300b70-ffffffff81300b7d: should_fail_alloc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81367fd0)
Location: mm/page_alloc.c:3848
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff81367fd0-ffffffff81367fe1: should_fail_alloc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e4000)
Location: mm/page_alloc.c:3933
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff813e4000-ffffffff813e4011: should_fail_alloc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81418d50)
Location: mm/page_alloc.c:2849
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff81418d50-ffffffff81418d61: should_fail_alloc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814458a0)
Location: mm/page_alloc.c:2920
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff814458a0-ffffffff814458b1: should_fail_alloc_page (STB_GLOBAL)
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010312958)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffff800010312958-ffff800010312974: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (c052e124)
Location: mm/page_alloc.c:3365
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
c052e124-c052e140: should_fail_alloc_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e3950)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
c0000000003e3950-c0000000003e3960: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a61e)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffe00021a61e-ffffffe00021a63a: should_fail_alloc_page.isra.0 (STB_LOCAL)
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273a30)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81273a30-ffffffff81273a3d: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812659a0)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812659a0-ffffffff812659ad: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812717d0)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812717d0-ffffffff812717dd: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281230)
Location: mm/page_alloc.c:3365
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81281230-ffffffff8128123d: should_fail_alloc_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
