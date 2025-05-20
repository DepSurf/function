# Function: <code>move_hugetlb_state</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81258710)
Location: mm/hugetlb.c:4839
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff81258710-ffffffff81258845: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126cde0)
Location: mm/hugetlb.c:4928
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff8126cde0-ffffffff8126cf19: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288210)
Location: mm/hugetlb.c:5033
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff81288210-ffffffff8128831f: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297e10)
Location: mm/hugetlb.c:5150
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff81297e10-ffffffff81297f1f: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cb4e0)
Location: mm/hugetlb.c:5649
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff812cb4e0-ffffffff812cb610: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d7100)
Location: mm/hugetlb.c:5661
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff812d7100-ffffffff812d7230: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de6f0)
Location: mm/hugetlb.c:5958
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff812de6f0-ffffffff812de7f5: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6295
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff81cc047d-ffffffff81cc04b4: move_hugetlb_state.cold (STB_LOCAL)
ffffffff81325a50-ffffffff81325bc3: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7036
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff81e7288a-ffffffff81e728d1: move_hugetlb_state.cold (STB_LOCAL)
ffffffff81394740-ffffffff8139491e: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void move_hugetlb_state(struct folio *old_folio, struct folio *new_folio, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7318
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff8206706b-ffffffff820670b1: move_hugetlb_state.cold (STB_LOCAL)
ffffffff814131c0-ffffffff81413361: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void move_hugetlb_state(struct folio *old_folio, struct folio *new_folio, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7417
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff820e6927-ffffffff820e696d: move_hugetlb_state.cold (STB_LOCAL)
ffffffff81446720-ffffffff814468c1: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void move_hugetlb_state(struct folio *old_folio, struct folio *new_folio, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7554
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff821c3a5a-ffffffff821c3a9f: move_hugetlb_state.cold (STB_LOCAL)
ffffffff814801c0-ffffffff81480364: move_hugetlb_state (STB_GLOBAL)
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
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010336258)
Location: mm/hugetlb.c:5150
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffff800010336258-ffff8000103363d8: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000410b10)
Location: mm/hugetlb.c:5150
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
c000000000410b10-c000000000410cec: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe000232296)
Location: mm/hugetlb.c:5150
Inline: False
```
**Symbols:**

```
ffffffe000232296-ffffffe00023235c: move_hugetlb_state (STB_GLOBAL)
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
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812903f0)
Location: mm/hugetlb.c:5150
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff812903f0-ffffffff812904ff: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81282080)
Location: mm/hugetlb.c:5150
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff81282080-ffffffff8128218f: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128e200)
Location: mm/hugetlb.c:5150
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff8128e200-ffffffff8128e30f: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void move_hugetlb_state(struct page *oldpage, struct page *newpage, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129dfa0)
Location: mm/hugetlb.c:5150
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff8129dfa0-ffffffff8129e0ad: move_hugetlb_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *old_folio</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio *new_folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *oldpage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *newpage</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
