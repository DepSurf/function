# Function: <code>put_compound_head</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_compound_head(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287d10)
Location: mm/gup.c:2125
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff81287d10-ffffffff81287e00: put_compound_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_compound_head(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291910)
Location: mm/gup.c:126
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:undo_dev_pagemap
```
**Symbols:**

```
ffffffff81291910-ffffffff812919fd: put_compound_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_compound_head(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81296c30)
Location: mm/gup.c:161
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
**Symbols:**

```
ffffffff81296c30-ffffffff81296d1d: put_compound_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_compound_head(struct page *page, int refs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d75e0)
Location: mm/gup.c:175
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
**Symbols:**

```
ffffffff812d75e0-ffffffff812d76ca: put_compound_head (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
