# Function: <code>folio_test_ksm</code>

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
In mm/debug.c (ffffffff81e6da7c)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81343dc2)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff81353be5)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135c0ee)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
```
In mm/ksm.c (ffffffff813a36a5)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff813b4359)
Location: include/linux/page-flags.h:686
Inline: True
```
```
In mm/memory-failure.c (ffffffff813dbadf)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_idle.c (ffffffff813e6505)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/proc/page.c (ffffffff814b1196)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/debug.c (ffffffff813adc6a)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813bbf6b)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff813ce0ba)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813d765e)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
```
In mm/ksm.c (ffffffff81423415)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff81434d1c)
Location: include/linux/page-flags.h:683
Inline: True
```
```
In mm/memory-failure.c (ffffffff8146274b)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_idle.c (ffffffff8146dfbe)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/proc/page.c (ffffffff81547b56)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/debug.c (ffffffff813e1ffd)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813f099a)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff81402959)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140bb6b)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
```
In mm/ksm.c (ffffffff81458675)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff8146878e)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
```
```
In mm/memory-failure.c (ffffffff81497d63)
Location: include/linux/page-flags.h:677
Inline: True
```
```
In mm/page_idle.c (ffffffff814a285c)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/proc/page.c (ffffffff8157f777)
Location: include/linux/page-flags.h:677
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/debug.c (ffffffff8140c80e)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81420205)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff8142ef77)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81438425)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
```
In mm/mempolicy.c (ffffffff81486fdc)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
```
```
In mm/ksm.c (ffffffff81492dd5)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81497e38)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
```
```
In mm/memory-failure.c (ffffffff814c75a1)
Location: include/linux/page-flags.h:679
Inline: True
```
```
In mm/page_idle.c (ffffffff814d36f9)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/proc/task_mmu.c (ffffffff8159e2f4)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff815b81b7)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
