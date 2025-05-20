# Function: <code>mem_cgroup_try_charge_delay</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129ac90)
Location: mm/memcontrol.c:5921
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8129ac90-ffffffff8129acd4: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5f30)
Location: mm/memcontrol.c:6213
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812b5f30-ffffffff812b5f74: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7e20)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812c7e20-ffffffff812c7e64: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036acf0)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffff80001036acf0-ffff80001036ad68: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c374)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
**Symbols:**

```
c055c374-c055c3c0: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a2a0)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
c00000000045a2a0-c00000000045a318: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002484c2)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
**Symbols:**

```
ffffffe0002484c2-ffffffe000248522: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0400)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812c0400-ffffffff812c0444: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b14d0)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812b14d0-ffffffff812b1514: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be210)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812be210-ffffffff812be254: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cec00)
Location: mm/memcontrol.c:6553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812cec00-ffffffff812cec44: mem_cgroup_try_charge_delay (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
