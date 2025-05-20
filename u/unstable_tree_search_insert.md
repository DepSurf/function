# Function: <code>unstable_tree_search_insert</code>

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
In mm/ksm.c (ffffffff811e638a)
Location: mm/ksm.c:1341
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812052ec)
Location: mm/ksm.c:1313
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81217295)
Location: mm/ksm.c:1342
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81222e55)
Location: mm/ksm.c:1879
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff8123e2f7)
Location: mm/ksm.c:1890
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81261671)
Location: mm/ksm.c:1920
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81275ed2)
Location: mm/ksm.c:1918
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812913b0)
Location: mm/ksm.c:1941
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
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
In mm/ksm.c (ffffffff812a1130)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rmap_item *unstable_tree_search_insert(struct rmap_item *rmap_item, struct page *page, struct page **tree_pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d5c80)
Location: mm/ksm.c:1923
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812d5c80-ffffffff812d6002: unstable_tree_search_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rmap_item *unstable_tree_search_insert(struct rmap_item *rmap_item, struct page *page, struct page **tree_pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e1770)
Location: mm/ksm.c:1924
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e1770-ffffffff812e1b0f: unstable_tree_search_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rmap_item *unstable_tree_search_insert(struct rmap_item *rmap_item, struct page *page, struct page **tree_pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e8f10)
Location: mm/ksm.c:1920
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e8f10-ffffffff812e92ac: unstable_tree_search_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rmap_item *unstable_tree_search_insert(struct rmap_item *rmap_item, struct page *page, struct page **tree_pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81330e30)
Location: mm/ksm.c:1916
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81330e30-ffffffff813311d1: unstable_tree_search_insert (STB_LOCAL)
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
In mm/ksm.c (ffffffff813a1b50)
Location: mm/ksm.c:1926
Inline: True
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff813a1b50-ffffffff813a2015: unstable_tree_search_insert.constprop.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff81420c90)
Location: mm/ksm.c:1942
Inline: True
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81420c90-ffffffff81421185: unstable_tree_search_insert.constprop.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff81455a70)
Location: mm/ksm.c:1988
Inline: True
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81455a70-ffffffff81455f3a: unstable_tree_search_insert.constprop.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff81490510)
Location: mm/ksm.c:2187
Inline: True
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81490510-ffffffff814909cb: unstable_tree_search_insert.constprop.0 (STB_LOCAL)
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
In mm/ksm.c (ffff800010340a80)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
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
In mm/ksm.c (0)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
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
In mm/ksm.c (c00000000041e150)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
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
In mm/ksm.c (ffffffe00023530a)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
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
In mm/ksm.c (ffffffff81299710)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
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
In mm/ksm.c (ffffffff8128b2d0)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
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
In mm/ksm.c (ffffffff81297520)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
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
In mm/ksm.c (ffffffff812a72eb)
Location: mm/ksm.c:1923
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
