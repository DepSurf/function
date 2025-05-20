# Function: <code>folio_free_swap</code>

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
bool folio_free_swap(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fe5c0)
Location: mm/swapfile.c:1579
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_folio_list
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff813fe5c0-ffffffff813fe6c1: folio_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool folio_free_swap(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81431560)
Location: mm/swapfile.c:1561
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_folio_list
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81431560-ffffffff814315f5: folio_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool folio_free_swap(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146a950)
Location: mm/swapfile.c:1561
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_folio_list
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/migrate_device.c:__migrate_device_pages
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8146a950-ffffffff8146a9e1: folio_free_swap (STB_GLOBAL)
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
