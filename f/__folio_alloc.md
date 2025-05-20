# Function: <code>__folio_alloc</code>

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
struct folio *__folio_alloc(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81370eb0)
Location: mm/page_alloc.c:5454
Inline: False
Direct callers:
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff81370eb0-ffffffff81370f0c: __folio_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct folio *__folio_alloc(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ed380)
Location: mm/page_alloc.c:5578
Inline: False
Direct callers:
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff813ed380-ffffffff813ed3dc: __folio_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct folio *__folio_alloc(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81422220)
Location: mm/page_alloc.c:4506
Inline: False
Direct callers:
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/migrate.c:alloc_misplaced_dst_folio
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff81422220-ffffffff8142227c: __folio_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct folio *__folio_alloc(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144f050)
Location: mm/page_alloc.c:4598
Inline: False
Direct callers:
  - mm/migrate.c:alloc_misplaced_dst_folio
  - mm/migrate.c:alloc_migration_target
  - mm/khugepaged.c:alloc_charge_hpage
```
**Symbols:**

```
ffffffff8144f050-ffffffff8144f0a7: __folio_alloc (STB_GLOBAL)
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
