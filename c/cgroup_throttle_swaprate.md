# Function: <code>cgroup_throttle_swaprate</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_throttle_swaprate(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bfe80)
Location: mm/swapfile.c:3790
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812bfe80-ffffffff812bffae: cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_throttle_swaprate(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cba30)
Location: mm/swapfile.c:3810
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812cba30-ffffffff812cbb66: cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_throttle_swaprate(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812d25d0)
Location: mm/swapfile.c:3781
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812d25d0-ffffffff812d271a: cgroup_throttle_swaprate (STB_GLOBAL)
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
In mm/shmem.c (ffffffff812ba553)
Location: include/linux/swap.h:725
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff812e3056)
Location: include/linux/swap.h:725
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/huge_memory.c (ffffffff81344d65)
Location: include/linux/swap.h:725
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/shmem.c (ffffffff81317a81)
Location: include/linux/swap.h:635
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff8134397c)
Location: include/linux/swap.h:635
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/huge_memory.c (ffffffff813ba073)
Location: include/linux/swap.h:635
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/shmem.c (ffffffff8138af66)
Location: include/linux/swap.h:645
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff813bba03)
Location: include/linux/swap.h:645
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/huge_memory.c (ffffffff8143c1c3)
Location: include/linux/swap.h:645
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
