# Function: <code>folio_raw_mapping</code>

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
In mm/util.c (ffffffff8131de83)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/util.c:page_rmapping
```
```
In mm/rmap.c (ffffffff8135cab7)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced
```
```
In mm/ksm.c (ffffffff813a36b9)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/page_idle.c (ffffffff813e64f7)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
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
In mm/util.c (ffffffff813919a3)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/util.c:page_rmapping
```
```
In mm/rmap.c (ffffffff813d715b)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced
```
```
In mm/ksm.c (ffffffff81423429)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/page_idle.c (ffffffff8146dfa8)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
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
In mm/util.c (ffffffff813c4383)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/util.c:page_rmapping
```
```
In mm/rmap.c (ffffffff8140c054)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced
```
```
In mm/ksm.c (ffffffff81458688)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/page_idle.c (ffffffff814a2846)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
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
In mm/memory.c (ffffffff81414cf4)
Location: mm/internal.h:79
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/rmap.c (ffffffff814388f1)
Location: mm/internal.h:79
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced
```
```
In mm/ksm.c (ffffffff81492de8)
Location: mm/internal.h:79
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/page_idle.c (ffffffff814d36e3)
Location: mm/internal.h:79
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
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
