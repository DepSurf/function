# Function: <code>unmap_and_move_huge_page</code>

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
In mm/migrate.c (ffffffff811f2396)
Location: mm/migrate.c:1014
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff81211c14)
Location: mm/migrate.c:1193
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff81223df4)
Location: mm/migrate.c:1202
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff8122f713)
Location: mm/migrate.c:1188
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff8124d233)
Location: mm/migrate.c:1260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff81270cf5)
Location: mm/migrate.c:1260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff81285305)
Location: mm/migrate.c:1284
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff8129f981)
Location: mm/migrate.c:1279
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff812b0d21)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unmap_and_move_huge_page(new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, struct page *hpage, int force, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e5e30)
Location: mm/migrate.c:1278
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff812e5e30-ffffffff812e613e: unmap_and_move_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unmap_and_move_huge_page(new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, struct page *hpage, int force, enum migrate_mode mode, int reason, struct list_head *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f11f0)
Location: mm/migrate.c:1259
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff812f11f0-ffffffff812f15ae: unmap_and_move_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unmap_and_move_huge_page(new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, struct page *hpage, int force, enum migrate_mode mode, int reason, struct list_head *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f74f0)
Location: mm/migrate.c:1239
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff812f74f0-ffffffff812f78ac: unmap_and_move_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int unmap_and_move_huge_page(new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, struct page *hpage, int force, enum migrate_mode mode, int reason, struct list_head *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1276
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff81341b50-ffffffff81341f16: unmap_and_move_huge_page (STB_LOCAL)
ffffffff81cc259d-ffffffff81cc25be: unmap_and_move_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int unmap_and_move_huge_page(new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, struct page *hpage, int force, enum migrate_mode mode, int reason, struct list_head *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1190
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff813b3800-ffffffff813b3ebc: unmap_and_move_huge_page (STB_LOCAL)
ffffffff81e74b4a-ffffffff81e74b6a: unmap_and_move_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int unmap_and_move_huge_page(new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, struct page *hpage, int force, enum migrate_mode mode, int reason, struct list_head *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1261
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff81434660-ffffffff81434b63: unmap_and_move_huge_page (STB_LOCAL)
ffffffff82067a1e-ffffffff82067a38: unmap_and_move_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unmap_and_move_huge_page(new_folio_t *get_new_folio, free_folio_t *put_new_folio, long unsigned int private, struct folio *src, int force, enum migrate_mode mode, int reason, struct list_head *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469fb0)
Location: mm/migrate.c:1352
Inline: False
Direct callers:
  - mm/migrate.c:migrate_hugetlbs
```
**Symbols:**

```
ffffffff81469fb0-ffffffff8146a35c: unmap_and_move_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unmap_and_move_huge_page(new_folio_t *get_new_folio, free_folio_t *put_new_folio, long unsigned int private, struct folio *src, int force, enum migrate_mode mode, int reason, struct list_head *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498f80)
Location: mm/migrate.c:1365
Inline: False
Direct callers:
  - mm/migrate.c:migrate_hugetlbs
```
**Symbols:**

```
ffffffff81498f80-ffffffff81499320: unmap_and_move_huge_page (STB_LOCAL)
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
In mm/migrate.c (ffff800010351204)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (0)
Location: mm/migrate.c:1280
Inline: True
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
In mm/migrate.c (c000000000437510)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffe00023fb28)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff812a9301)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff8129ac61)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff812a7111)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/migrate.c (ffffffff812b7421)
Location: mm/migrate.c:1280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head *ret</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>new_folio_t *get_new_folio</code>
</li>
<li>
<b>Param added. </b>
<code>free_folio_t *put_new_folio</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio *src</code>
</li>
<li>
<b>Param removed. </b>
<code>new_page_t *get_new_page</code>
</li>
<li>
<b>Param removed. </b>
<code>free_page_t *put_new_page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *hpage</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
