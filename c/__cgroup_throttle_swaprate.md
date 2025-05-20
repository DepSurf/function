# Function: <code>__cgroup_throttle_swaprate</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __cgroup_throttle_swaprate(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81317ed0)
Location: mm/swapfile.c:3782
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
ffffffff81317ed0-ffffffff8131801a: __cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __cgroup_throttle_swaprate(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813835b0)
Location: mm/swapfile.c:3637
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
ffffffff813835b0-ffffffff813836a6: __cgroup_throttle_swaprate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __cgroup_throttle_swaprate(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81400fd0)
Location: mm/swapfile.c:3639
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
ffffffff81400fd0-ffffffff814010c6: __cgroup_throttle_swaprate (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
