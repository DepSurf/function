# Function: <code>warn_alloc</code>

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
void warn_alloc(gfp_t gfp_mask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ba900)
Location: mm/page_alloc.c:3014
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff811ba900-ffffffff811baa66: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c2930)
Location: mm/page_alloc.c:3216
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811c2930-ffffffff811c2ae5: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d7730)
Location: mm/page_alloc.c:3284
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811d7730-ffffffff811d78c3: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3406
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff811fad4a-ffffffff811fae46: warn_alloc.cold.115 (STB_LOCAL)
ffffffff811f8a80-ffffffff811f8b08: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3568
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff8120d5f4-ffffffff8120d6ef: warn_alloc.cold.119 (STB_LOCAL)
ffffffff8120b000-ffffffff8120b08d: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3736
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81273aab-ffffffff81273ba6: warn_alloc.cold (STB_LOCAL)
ffffffff81271290-ffffffff8127131f: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff812828e2-ffffffff812829c1: warn_alloc.cold (STB_LOCAL)
ffffffff812800d0-ffffffff8128015f: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3838
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff812b4984-ffffffff812b4a63: warn_alloc.cold (STB_LOCAL)
ffffffff812b2930-ffffffff812b29bf: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3989
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81be7ca4-ffffffff81be7d83: warn_alloc.cold (STB_LOCAL)
ffffffff812be4a0-ffffffff812be52f: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4036
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81bd9a9e-ffffffff81bd9b7a: warn_alloc.cold (STB_LOCAL)
ffffffff812c3530-ffffffff812c35bf: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4207
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81cbd9c7-ffffffff81cbda18: warn_alloc.cold (STB_LOCAL)
ffffffff813072e0-ffffffff81307433: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4250
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81e6f836-ffffffff81e6f883: warn_alloc.cold (STB_LOCAL)
ffffffff8136f600-ffffffff8136f783: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ebbb0)
Location: mm/page_alloc.c:4335
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff813ebbb0-ffffffff813ebd96: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81420bc0)
Location: mm/page_alloc.c:3278
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81420bc0-ffffffff81420da1: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144d980)
Location: mm/page_alloc.c:3368
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff8144d980-ffffffff8144db61: warn_alloc (STB_GLOBAL)
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
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317f60)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffff800010317f60-ffff8000103180c4: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05324b8)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c05324b8-c053262c: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ea540)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
c0000000003ea540-c0000000003ea70c: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021de0c)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffe00021de0c-ffffffe00021df22: warn_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff8127af32-ffffffff8127b011: warn_alloc.cold (STB_LOCAL)
ffffffff81278720-ffffffff812787af: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff8126ce12-ffffffff8126cef1: warn_alloc.cold (STB_LOCAL)
ffffffff8126a610-ffffffff8126a69f: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81278cd2-ffffffff81278db1: warn_alloc.cold (STB_LOCAL)
ffffffff812764c0-ffffffff8127654f: warn_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t *nodemask, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3723
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff812888c2-ffffffff812889a1: warn_alloc.cold (STB_LOCAL)
ffffffff81286080-ffffffff8128610f: warn_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>nodemask_t *nodemask</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp_mask, fmt, (anon)</code> ➡️ <code>gfp_mask, nodemask, fmt, (anon)</code>
</li>
</ul>
</details>
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
