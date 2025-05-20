# Function: <code>swapin_readahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811d2c60)
Location: mm/swap_state.c:465
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811d2c60-ffffffff811d2e0b: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811f0a50)
Location: mm/swap_state.c:471
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811f0a50-ffffffff811f0c54: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81201450)
Location: mm/swap_state.c:471
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81201450-ffffffff81201654: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120c2e0)
Location: mm/swap_state.c:490
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8120c2e0-ffffffff8120c4f6: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812259d0)
Location: mm/swap_state.c:554
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812259d0-ffffffff81225c67: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81248370)
Location: mm/swap_state.c:791
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81248370-ffffffff8124882c: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125c940)
Location: mm/swap_state.c:753
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8125c940-ffffffff8125ce09: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81277b20)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81277b20-ffffffff81277f8f: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81287610)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81287610-ffffffff81287a7f: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b9e60)
Location: mm/swap_state.c:799
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812b9e60-ffffffff812b9e8c: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c58d0)
Location: mm/swap_state.c:893
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812c58d0-ffffffff812c58fc: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cc580)
Location: mm/swap_state.c:862
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812cc580-ffffffff812cc5ac: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:849
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81cbeb0e-ffffffff81cbeb2a: swapin_readahead.cold (STB_LOCAL)
ffffffff81311870-ffffffff813118cd: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:863
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81e70c9f-ffffffff81e70cbc: swapin_readahead.cold (STB_LOCAL)
ffffffff8137c9b0-ffffffff8137ca24: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:847
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff82065c36-ffffffff82065c53: swapin_readahead.cold (STB_LOCAL)
ffffffff813fa1a0-ffffffff813fa214: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:856
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff820e53c8-ffffffff820e53e5: swapin_readahead.cold (STB_LOCAL)
ffffffff8142d0d0-ffffffff8142d144: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:878
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff821c255e-ffffffff821c2573: swapin_readahead.cold (STB_LOCAL)
ffffffff814667e0-ffffffff814668e4: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff8000103221b0)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffff8000103221b0-ffff800010322594: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c053a830)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
c053a830-c053ac88: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f7bb0)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
c0000000003f7bb0-c0000000003f81a8: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe0002231dc)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffe0002231dc-ffffffe000223510: swapin_readahead (STB_GLOBAL)
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
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127fbe0)
Location: mm/swap_state.c:739
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8127fbe0-ffffffff81280054: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81271a80)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81271a80-ffffffff81271ecc: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127da00)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8127da00-ffffffff8127de6f: swapin_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128d5b0)
Location: mm/swap_state.c:781
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8128d5b0-ffffffff8128da1f: swapin_readahead (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
