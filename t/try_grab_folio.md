# Function: <code>try_grab_folio</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct folio *try_grab_folio(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81337f10)
Location: mm/gup.c:124
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff81337f10-ffffffff81337ffa: try_grab_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct folio *try_grab_folio(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813af420)
Location: mm/gup.c:124
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff813af420-ffffffff813af782: try_grab_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct folio *try_grab_folio(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e3b20)
Location: mm/gup.c:126
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/hugetlb.c:follow_hugetlb_page
```
**Symbols:**

```
ffffffff813e3b20-ffffffff813e3f27: try_grab_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct folio *try_grab_folio(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140e390)
Location: mm/gup.c:126
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8140e390-ffffffff8140e785: try_grab_folio (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
