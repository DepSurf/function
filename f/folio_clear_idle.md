# Function: <code>folio_clear_idle</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f3d6d)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff81305aa2)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/rmap.c (ffffffff8135b5ce)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_idle.c (ffffffff813e63d3)
Location: include/linux/page-flags.h:614
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135e05d)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff81370997)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/rmap.c (ffffffff813d5ea2)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_idle.c (ffffffff8146debe)
Location: include/linux/page-flags.h:593
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390eae)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff813a2bbd)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/rmap.c (ffffffff8140afb2)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_idle.c (ffffffff814a29be)
Location: include/linux/page-flags.h:587
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bab99)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/swap.c (ffffffff813cc83d)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/rmap.c (ffffffff814377aa)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_idle.c (ffffffff814d385b)
Location: include/linux/page-flags.h:589
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
