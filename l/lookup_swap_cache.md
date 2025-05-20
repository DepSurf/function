# Function: <code>lookup_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811d2a60)
Location: mm/swap_state.c:275
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811d2a60-ffffffff811d2abb: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811f07e0)
Location: mm/swap_state.c:282
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811f07e0-ffffffff811f0831: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812011d0)
Location: mm/swap_state.c:282
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812011d0-ffffffff81201228: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120c020)
Location: mm/swap_state.c:300
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8120c020-ffffffff8120c0a3: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81225650)
Location: mm/swap_state.c:331
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_readahead_detect
```
**Symbols:**

```
ffffffff81225650-ffffffff8122576e: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81247bf0)
Location: mm/swap_state.c:333
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81247bf0-ffffffff81247d02: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125c1c0)
Location: mm/swap_state.c:309
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8125c1c0-ffffffff8125c2d2: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81277390)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81277390-ffffffff812774b8: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81286e70)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81286e70-ffffffff81286f98: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b93f0)
Location: mm/swap_state.c:309
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812b93f0-ffffffff812b951b: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c4d80)
Location: mm/swap_state.c:369
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812c4d80-ffffffff812c4eba: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cba10)
Location: mm/swap_state.c:339
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812cba10-ffffffff812cbb56: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:334
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81cbea32-ffffffff81cbea46: lookup_swap_cache.cold (STB_LOCAL)
ffffffff81310ae0-ffffffff81310c80: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:339
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81e70bb9-ffffffff81e70bce: lookup_swap_cache.cold (STB_LOCAL)
ffffffff8137b890-ffffffff8137baad: lookup_swap_cache (STB_GLOBAL)
```
</details>
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
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010321858)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffff800010321858-ffff800010321a94: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c053a040)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c053a040-c053a1d0: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f6fb0)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c0000000003f6fb0-c0000000003f7208: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe000222aa2)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffe000222aa2-ffffffe000222c06: lookup_swap_cache (STB_GLOBAL)
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
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127f4c0)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8127f4c0-ffffffff8127f5e8: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812712e0)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812712e0-ffffffff81271408: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127d260)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8127d260-ffffffff8127d388: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *lookup_swap_cache(swp_entry_t entry, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128ce20)
Location: mm/swap_state.c:310
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8128ce20-ffffffff8128cf57: lookup_swap_cache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
