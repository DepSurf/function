# Function: <code>is_huge_zero_page</code>

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
In mm/huge_memory.c (ffffffff811f5df7)
Location: include/linux/huge_mm.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/proc/page.c (ffffffff812882ad)
Location: include/linux/huge_mm.h:155
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff811b2be1)
Location: include/linux/huge_mm.h:145
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff811d5140)
Location: include/linux/huge_mm.h:145
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/swap_state.c (ffffffff811f06b5)
Location: include/linux/huge_mm.h:145
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff811ff14b)
Location: include/linux/huge_mm.h:145
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff81215f45)
Location: include/linux/huge_mm.h:145
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/page.c (ffffffff812b5749)
Location: include/linux/huge_mm.h:145
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
In mm/swap.c (ffffffff811c3268)
Location: include/linux/huge_mm.h:149
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff811e5150)
Location: include/linux/huge_mm.h:149
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/swap_state.c (ffffffff8120109e)
Location: include/linux/huge_mm.h:149
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81210996)
Location: include/linux/huge_mm.h:149
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812286c8)
Location: include/linux/huge_mm.h:149
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/page.c (ffffffff812cafcd)
Location: include/linux/huge_mm.h:149
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
In mm/swap.c (ffffffff811cb500)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff811ef82a)
Location: include/linux/huge_mm.h:216
Inline: True
```
```
In mm/swap_state.c (ffffffff8120beee)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff8121c359)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff81231d7c)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/page.c (ffffffff812d8407)
Location: include/linux/huge_mm.h:216
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
In mm/swap.c (ffffffff811e088d)
Location: include/linux/huge_mm.h:223
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff81206921)
Location: include/linux/huge_mm.h:223
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/swap_state.c (ffffffff812254ee)
Location: include/linux/huge_mm.h:223
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff812372f6)
Location: include/linux/huge_mm.h:223
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b1f9)
Location: include/linux/huge_mm.h:223
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81252aa6)
Location: include/linux/huge_mm.h:223
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/page.c (ffffffff812fcb07)
Location: include/linux/huge_mm.h:223
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
In mm/swap.c (ffffffff81202100)
Location: include/linux/huge_mm.h:224
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff8122789d)
Location: include/linux/huge_mm.h:224
Inline: True
```
```
In mm/swap_state.c (ffffffff81247a8e)
Location: include/linux/huge_mm.h:224
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff8125a83d)
Location: include/linux/huge_mm.h:224
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126de24)
Location: include/linux/huge_mm.h:224
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81276ea0)
Location: include/linux/huge_mm.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/page.c (ffffffff8132a724)
Location: include/linux/huge_mm.h:224
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
In mm/swap.c (ffffffff81214a80)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff8123b059)
Location: include/linux/huge_mm.h:230
Inline: True
```
```
In mm/swap_state.c (ffffffff8125c05e)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff8126e6c4)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81282c94)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81288703)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/page.c (ffffffff81341a81)
Location: include/linux/huge_mm.h:230
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
In mm/swap.c (ffffffff81223d23)
Location: include/linux/huge_mm.h:245
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff8124c265)
Location: include/linux/huge_mm.h:245
Inline: True
```
```
In mm/swap_state.c (ffffffff81277217)
Location: include/linux/huge_mm.h:245
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81289d00)
Location: include/linux/huge_mm.h:245
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812a333f)
Location: include/linux/huge_mm.h:245
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (ffffffff81369f30)
Location: include/linux/huge_mm.h:245
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
In mm/swap.c (ffffffff81231ab3)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff8125a73d)
Location: include/linux/huge_mm.h:250
Inline: True
```
```
In mm/madvise.c (ffffffff81284ed5)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81286cf7)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81299870)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812ae734)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b483f)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (ffffffff81382150)
Location: include/linux/huge_mm.h:250
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
In mm/swap.c (ffffffff8125e673)
Location: include/linux/huge_mm.h:284
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff81288bd3)
Location: include/linux/huge_mm.h:284
Inline: True
```
```
In mm/memory.c (ffffffff8129003f)
Location: include/linux/huge_mm.h:284
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/madvise.c (ffffffff812b70b1)
Location: include/linux/huge_mm.h:284
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812b9276)
Location: include/linux/huge_mm.h:284
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff812ceb31)
Location: include/linux/huge_mm.h:284
Inline: True
```
```
In mm/migrate.c (ffffffff812e3d91)
Location: include/linux/huge_mm.h:284
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ea1b8)
Location: include/linux/huge_mm.h:284
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In fs/proc/page.c (ffffffff813cc780)
Location: include/linux/huge_mm.h:284
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
In mm/swap.c (ffffffff812687ca)
Location: include/linux/huge_mm.h:290
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff812928b3)
Location: include/linux/huge_mm.h:290
Inline: True
```
```
In mm/memory.c (ffffffff8129aacf)
Location: include/linux/huge_mm.h:290
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/madvise.c (ffffffff812c1ff8)
Location: include/linux/huge_mm.h:290
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812c4c06)
Location: include/linux/huge_mm.h:290
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff812da471)
Location: include/linux/huge_mm.h:290
Inline: True
```
```
In mm/migrate.c (ffffffff812efaf0)
Location: include/linux/huge_mm.h:290
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812f538b)
Location: include/linux/huge_mm.h:290
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In fs/proc/page.c (ffffffff813de3e8)
Location: include/linux/huge_mm.h:290
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
In mm/swap.c (ffffffff8126e4b0)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff812983d4)
Location: include/linux/huge_mm.h:296
Inline: True
```
```
In mm/swap_state.c (ffffffff812cb896)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff812e1cd9)
Location: include/linux/huge_mm.h:296
Inline: True
```
```
In mm/migrate.c (ffffffff812f5473)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812fcdcd)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In fs/proc/page.c (ffffffff813e51c4)
Location: include/linux/huge_mm.h:296
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
In mm/swap.c (ffffffff812ab4b8)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff812d8e12)
Location: include/linux/huge_mm.h:296
Inline: True
```
```
In mm/swap_state.c (ffffffff81310a13)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81328dbb)
Location: include/linux/huge_mm.h:296
Inline: True
```
```
In mm/migrate.c (ffffffff8133fa73)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81343991)
Location: include/linux/huge_mm.h:296
Inline: True
Inline callers:
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In fs/proc/page.c (ffffffff81436d94)
Location: include/linux/huge_mm.h:296
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
In mm/swap.c (ffffffff81305299)
Location: include/linux/huge_mm.h:286
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff81338db8)
Location: include/linux/huge_mm.h:286
Inline: True
```
```
In mm/swap_state.c (ffffffff8137b7a2)
Location: include/linux/huge_mm.h:286
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff8139805a)
Location: include/linux/huge_mm.h:286
Inline: True
```
```
In mm/migrate_device.c (ffffffff813b6ee9)
Location: include/linux/huge_mm.h:286
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c068d)
Location: include/linux/huge_mm.h:286
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/proc/page.c (ffffffff814b1819)
Location: include/linux/huge_mm.h:286
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
In mm/swap.c (ffffffff8136f54d)
Location: include/linux/huge_mm.h:271
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff813b0660)
Location: include/linux/huge_mm.h:271
Inline: True
```
```
In mm/swap_state.c (ffffffff813f9112)
Location: include/linux/huge_mm.h:271
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81417dd5)
Location: include/linux/huge_mm.h:271
Inline: True
```
```
In mm/migrate_device.c (ffffffff81438a32)
Location: include/linux/huge_mm.h:271
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81442dd1)
Location: include/linux/huge_mm.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/proc/page.c (ffffffff8154827c)
Location: include/linux/huge_mm.h:271
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
In mm/swap.c (ffffffff813a166d)
Location: include/linux/huge_mm.h:233
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/swap_state.c (ffffffff8142bee2)
Location: include/linux/huge_mm.h:233
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff8144b375)
Location: include/linux/huge_mm.h:233
Inline: True
```
```
In mm/migrate_device.c (ffffffff8146f1a0)
Location: include/linux/huge_mm.h:233
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814786a0)
Location: include/linux/huge_mm.h:233
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/proc/page.c (ffffffff8157fe4f)
Location: include/linux/huge_mm.h:233
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
In mm/swap.c (ffffffff813cb2ed)
Location: include/linux/huge_mm.h:354
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/swap_state.c (ffffffff81465642)
Location: include/linux/huge_mm.h:354
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81484d5e)
Location: include/linux/huge_mm.h:354
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate_device.c (ffffffff8149dca1)
Location: include/linux/huge_mm.h:354
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a7dc2)
Location: include/linux/huge_mm.h:354
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/proc/page.c (ffffffff815b883e)
Location: include/linux/huge_mm.h:354
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
In mm/swap.c (ffff8000102c1768)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffff8000102f20f4)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/madvise.c (ffff80001031f1bc)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffff800010321644)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffff800010338590)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffff800010355dc0)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (ffff80001045022c)
Location: include/linux/huge_mm.h:250
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
In mm/swap.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
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
In mm/swap.c (c00000000037b520)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (c0000000003b8084)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/madvise.c (c0000000003f3cec)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (c0000000003f6cbc)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (c00000000041316c)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434928)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c00000000043c180)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (c000000000568230)
Location: include/linux/huge_mm.h:250
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
In mm/swap.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/huge_mm.h:377
Inline: True
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
In mm/swap.c (ffffffff8122a103)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff81252d8d)
Location: include/linux/huge_mm.h:250
Inline: True
```
```
In mm/madvise.c (ffffffff8127d525)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127f347)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81291e50)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a6d14)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ace1f)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (ffffffff8137a730)
Location: include/linux/huge_mm.h:250
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
In mm/swap.c (ffffffff8121d223)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff81245ad7)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/madvise.c (ffffffff8126f323)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81271167)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff81283aa0)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812987b4)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8129debb)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (ffffffff8136b200)
Location: include/linux/huge_mm.h:250
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
In mm/swap.c (ffffffff81227ea3)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff81250b2d)
Location: include/linux/huge_mm.h:250
Inline: True
```
```
In mm/madvise.c (ffffffff8127b2c5)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127d0e7)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff8128fc60)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a4b24)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812aac2f)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (ffffffff81378200)
Location: include/linux/huge_mm.h:250
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
In mm/swap.c (ffffffff812371e3)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff812604b3)
Location: include/linux/huge_mm.h:250
Inline: True
```
```
In mm/madvise.c (ffffffff8128ae95)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8128cca7)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/mempolicy.c (ffffffff8129f0f1)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5682)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812baf7f)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/page.c (ffffffff8138bcb0)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
