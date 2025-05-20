# Function: <code>__alloc_pages_may_oom</code>

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
In mm/page_alloc.c (ffffffff81196fc1)
Location: mm/page_alloc.c:2683
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/page_alloc.c (ffffffff811aa718)
Location: mm/page_alloc.c:3005
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/page_alloc.c (ffffffff811bad1f)
Location: mm/page_alloc.c:3052
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/page_alloc.c (ffffffff811c2de7)
Location: mm/page_alloc.c:3267
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/page_alloc.c (ffffffff811d79e3)
Location: mm/page_alloc.c:3329
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/page_alloc.c (ffffffff811f9097)
Location: mm/page_alloc.c:3451
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120b645)
Location: mm/page_alloc.c:3613
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812718b9)
Location: mm/page_alloc.c:3781
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81280769)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b2ef1)
Location: mm/page_alloc.c:3882
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bea2e)
Location: mm/page_alloc.c:4033
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c3ab2)
Location: mm/page_alloc.c:4080
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8130794b)
Location: mm/page_alloc.c:4253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *__alloc_pages_may_oom(gfp_t gfp_mask, unsigned int order, const struct alloc_context *ac, long unsigned int *did_some_progress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4296
Inline: False
```
**Symbols:**

```
ffffffff8136f2e0-ffffffff8136f4b3: __alloc_pages_may_oom (STB_LOCAL)
ffffffff81e6f821-ffffffff81e6f836: __alloc_pages_may_oom.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *__alloc_pages_may_oom(gfp_t gfp_mask, unsigned int order, const struct alloc_context *ac, long unsigned int *did_some_progress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4381
Inline: False
```
**Symbols:**

```
ffffffff813eb860-ffffffff813eba33: __alloc_pages_may_oom (STB_LOCAL)
ffffffff820655cb-ffffffff820655e0: __alloc_pages_may_oom.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *__alloc_pages_may_oom(gfp_t gfp_mask, unsigned int order, const struct alloc_context *ac, long unsigned int *did_some_progress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3324
Inline: False
```
**Symbols:**

```
ffffffff81420880-ffffffff81420a4c: __alloc_pages_may_oom (STB_LOCAL)
ffffffff820e4dc4-ffffffff820e4dd9: __alloc_pages_may_oom.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *__alloc_pages_may_oom(gfp_t gfp_mask, unsigned int order, const struct alloc_context *ac, long unsigned int *did_some_progress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3414
Inline: False
```
**Symbols:**

```
ffffffff8144d640-ffffffff8144d80c: __alloc_pages_may_oom (STB_LOCAL)
ffffffff821c1a93-ffffffff821c1aa8: __alloc_pages_may_oom.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010318758)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0532938)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003eaf98)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021dfb2)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278db9)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126aca9)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276b59)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81286703)
Location: mm/page_alloc.c:3767
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
