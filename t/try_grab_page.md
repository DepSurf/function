# Function: <code>try_grab_page</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff812878d0)
Location: mm/gup.c:147
Inline: True
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff812878d0-ffffffff8128797d: try_grab_page.part.0 (STB_LOCAL)
ffffffff81288230-ffffffff8128828a: try_grab_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff81291710)
Location: mm/gup.c:169
Inline: True
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81291710-ffffffff812917bd: try_grab_page.part.0 (STB_LOCAL)
ffffffff81291f10-ffffffff81291f6a: try_grab_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81297a30)
Location: mm/gup.c:197
Inline: True
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:follow_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81297a30-ffffffff81297b35: try_grab_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d8470)
Location: mm/gup.c:209
Inline: True
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:follow_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff812d8470-ffffffff812d8575: try_grab_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81338400)
Location: mm/gup.c:202
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:follow_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81338400-ffffffff813384e4: try_grab_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813afbf0)
Location: mm/gup.c:214
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff813afbf0-ffffffff813afd1d: try_grab_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e4300)
Location: mm/gup.c:225
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff813e4300-ffffffff813e441a: try_grab_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_grab_page(struct page *page, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140eb20)
Location: mm/gup.c:225
Inline: False
Direct callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff8140eb20-ffffffff8140ec34: try_grab_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
