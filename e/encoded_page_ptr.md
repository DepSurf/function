# Function: <code>encoded_page_ptr</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136f51d)
Location: include/linux/mm_types.h:284
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/mmu_gather.c (ffffffff813cceb2)
Location: include/linux/mm_types.h:284
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_rmaps
  - mm/mmu_gather.c:tlb_flush_rmaps
```
```
In mm/swap_state.c (ffffffff813f91da)
Location: include/linux/mm_types.h:284
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
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
In mm/swap.c (ffffffff813a163d)
Location: include/linux/mm_types.h:260
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/mmu_gather.c (ffffffff81401812)
Location: include/linux/mm_types.h:260
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_rmaps
  - mm/mmu_gather.c:tlb_flush_rmaps
```
```
In mm/swap_state.c (ffffffff8142bfaa)
Location: include/linux/mm_types.h:260
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
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
In mm/swap.c (ffffffff813cb2bd)
Location: include/linux/mm_types.h:235
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/mmu_gather.c (ffffffff8142dd69)
Location: include/linux/mm_types.h:235
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_rmap_batch
```
```
In mm/swap_state.c (ffffffff8146570a)
Location: include/linux/mm_types.h:235
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
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
