# Function: <code>folio_get_anon_vma</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct anon_vma *folio_get_anon_vma(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813dabf0)
Location: mm/rmap.c:492
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff813dabf0-ffffffff813dacb7: folio_get_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct anon_vma *folio_get_anon_vma(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140f330)
Location: mm/rmap.c:494
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8140f330-ffffffff8140f3f7: folio_get_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct anon_vma *folio_get_anon_vma(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143bcf0)
Location: mm/rmap.c:500
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/userfaultfd.c:move_pages_pte
```
**Symbols:**

```
ffffffff8143bcf0-ffffffff8143bdae: folio_get_anon_vma (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
