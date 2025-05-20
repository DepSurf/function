# Function: <code>PageKsm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In mm/rmap.c (ffffffff811cc44b)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/swapfile.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:330
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d8312)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff811e4afd)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811e949a)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff811f282e)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812060d5)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812121ad)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff81226e5a)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff8122dceb)
Location: include/linux/page-flags.h:403
Inline: True
```
```
In fs/proc/page.c (ffffffff812b546b)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e901d)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff811f4b18)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811fa7ea)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff8120322e)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812180f5)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff81224326)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff812393f6)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff8124023b)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In fs/proc/page.c (ffffffff812caccc)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f42af)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff811ff9da)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81205145)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff8120e64e)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81223c75)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8122fc93)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff81244a1a)
Location: include/linux/page-flags.h:422
Inline: True
```
```
In mm/page_idle.c (ffffffff8124c0db)
Location: include/linux/page-flags.h:422
Inline: True
```
```
In fs/proc/page.c (ffffffff812d815c)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120bfc1)
Location: include/linux/page-flags.h:423
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff81218105)
Location: include/linux/page-flags.h:423
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8121e0f5)
Location: include/linux/page-flags.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff81229b85)
Location: include/linux/page-flags.h:423
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff8123f2c5)
Location: include/linux/page-flags.h:423
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8124d804)
Location: include/linux/page-flags.h:423
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff8126490a)
Location: include/linux/page-flags.h:423
Inline: True
```
```
In mm/page_idle.c (ffffffff8126c4bb)
Location: include/linux/page-flags.h:423
Inline: True
```
```
In fs/proc/page.c (ffffffff812fc85c)
Location: include/linux/page-flags.h:423
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122cb81)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff812391da)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8123ffb5)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff8124ae45)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81262a85)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff81270e61)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff8128906d)
Location: include/linux/page-flags.h:430
Inline: True
```
```
In mm/page_idle.c (ffffffff8129102b)
Location: include/linux/page-flags.h:430
Inline: True
```
```
In fs/proc/page.c (ffffffff8132a45b)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8123954a)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812400d1)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff8124d75e)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812546b5)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff8125f495)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81277305)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff81285473)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff8129dfbd)
Location: include/linux/page-flags.h:447
Inline: True
```
```
In mm/page_idle.c (ffffffff812a604b)
Location: include/linux/page-flags.h:447
Inline: True
```
```
In fs/proc/page.c (ffffffff8134177b)
Location: include/linux/page-flags.h:447
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8124a5aa)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81252214)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff8125f76a)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81266965)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff8127a155)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81292c45)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8129faa6)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff812b9172)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (ffffffff812c176e)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffffffff81369b9b)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81258889)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812607f4)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff8126df7a)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81275285)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff81289c35)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812a29c5)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812b0e46)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff812cb062)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (ffffffff812d369e)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffffffff81381dbb)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81287222)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81290f7d)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff8129e823)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a5dbc)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff812bcaf1)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812d7145)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812e62f0)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff8130110d)
Location: include/linux/page-flags.h:496
Inline: True
```
```
In mm/page_idle.c (ffffffff81309150)
Location: include/linux/page-flags.h:496
Inline: True
```
```
In fs/proc/page.c (ffffffff813cc3eb)
Location: include/linux/page-flags.h:496
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81be750c)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8129ba41)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff812a9bd9)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b123c)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff812c8621)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812e2bf5)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812f1760)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff8130d15d)
Location: include/linux/page-flags.h:500
Inline: True
```
```
In mm/page_idle.c (ffffffff81314fc0)
Location: include/linux/page-flags.h:500
Inline: True
```
```
In fs/proc/page.c (ffffffff813de02c)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81bd93a5)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812a0b25)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff812af064)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b690c)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff812cefd1)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812ea385)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812f7a60)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff8131371d)
Location: include/linux/page-flags.h:500
Inline: True
```
```
In mm/page_idle.c (ffffffff8131b700)
Location: include/linux/page-flags.h:500
Inline: True
```
```
In fs/proc/page.c (ffffffff813e4e1b)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81cbbde6)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812e1c45)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff812f085a)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812f9645)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff81314571)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff813322a5)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff813420d0)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff81360431)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_idle.c (ffffffff813689d0)
Location: include/linux/page-flags.h:520
Inline: True
```
```
In fs/proc/page.c (ffffffff814369eb)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81e6da68)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81343dba)
Location: include/linux/page-flags.h:692
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
In mm/mprotect.c (ffffffff81353bd0)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135cd45)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/ksm.c (ffffffff813a30bd)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff813b4345)
Location: include/linux/page-flags.h:692
Inline: True
```
```
In mm/memory-failure.c (ffffffff813dbacf)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff814b1186)
Location: include/linux/page-flags.h:692
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
In mm/debug.c (ffffffff813adc56)
Location: include/linux/page-flags.h:689
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mprotect.c (ffffffff813ce0a6)
Location: include/linux/page-flags.h:689
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813d7785)
Location: include/linux/page-flags.h:689
Inline: True
Inline callers:
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/ksm.c (ffffffff81422d39)
Location: include/linux/page-flags.h:689
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/memory-failure.c (ffffffff81462737)
Location: include/linux/page-flags.h:689
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff81547b46)
Location: include/linux/page-flags.h:689
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
In mm/debug.c (ffffffff813e1fe9)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mprotect.c (ffffffff81402945)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (ffffffff81457da9)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/memory-failure.c (ffffffff81497d56)
Location: include/linux/page-flags.h:683
Inline: True
```
```
In fs/proc/page.c (ffffffff8157f763)
Location: include/linux/page-flags.h:683
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
In mm/debug.c (ffffffff8140c7fa)
Location: include/linux/page-flags.h:685
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mempolicy.c (ffffffff81486ff4)
Location: include/linux/page-flags.h:685
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
```
```
In mm/ksm.c (ffffffff8148f4df)
Location: include/linux/page-flags.h:685
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/memory-failure.c (ffffffff814c758c)
Location: include/linux/page-flags.h:685
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159e2e0)
Location: include/linux/page-flags.h:685
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff815b81a3)
Location: include/linux/page-flags.h:685
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffff8000102f0888)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffff8000102f7b70)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffff8000103051c4)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff80001030b124)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffff800010324bf8)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffff800010342440)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffff800010351574)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffff80001036ea50)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (ffff800010379030)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffff80001044ffd8)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (c0513d6c)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c051a364)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (c0523450)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0527578)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (c053c6dc)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c0548154)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (c0552984)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (c056458c)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (c061325c)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (c0000000003b51a8)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0000000003c0af0)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (c0000000003d24e8)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003db170)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (c0000000003face8)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c00000000041fe60)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (c000000000437704)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (c00000000045f740)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (c00000000046c250)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (c000000000567fd0)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffe00020407a)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffe000208060)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffe000211316)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000214b44)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffe0002252fe)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffe00023664a)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffe00023fe48)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffe000250864)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e31c2)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81250ed9)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81258e44)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff812665ca)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126d8d5)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff81282215)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff8129afa5)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812a9426)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff812c3642)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (ffffffff812cbc7e)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffffffff8137a39b)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81243e19)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8124b2f4)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff81258ca1)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125f905)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff81273d35)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff8128cb65)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8129ad86)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff812b4682)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (ffffffff812bcaee)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffffffff8136ae6b)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8124ec79)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81256be4)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff8126436a)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126b675)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff81280025)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81298db5)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812a7236)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff812c1452)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (ffffffff812c9a8e)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffffffff81377e6b)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8125e5f9)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8126664e)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mprotect.c (ffffffff81273d2a)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8127b005)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff8128fd15)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812a8b95)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812b7541)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff812d1f12)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In mm/page_idle.c (ffffffff812da77e)
Location: include/linux/page-flags.h:480
Inline: True
```
```
In fs/proc/page.c (ffffffff8138b91b)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
