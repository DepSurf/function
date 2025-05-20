# Function: <code>swap_cluster_readahead</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81247f80)
Location: mm/swap_state.c:566
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff81247f80-ffffffff81248271: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125c560)
Location: mm/swap_state.c:528
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff8125c560-ffffffff8125c84e: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81277750)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff81277750-ffffffff81277a2e: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81287240)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff81287240-ffffffff8128751e: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b9a60)
Location: mm/swap_state.c:557
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff812b9a60-ffffffff812b9d6d: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c54d0)
Location: mm/swap_state.c:649
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff812c54d0-ffffffff812c57db: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cc180)
Location: mm/swap_state.c:618
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff812cc180-ffffffff812cc4a4: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:613
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff81cbeaa9-ffffffff81cbeb0e: swap_cluster_readahead.cold (STB_LOCAL)
ffffffff81311380-ffffffff81311681: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:623
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff81e70c3c-ffffffff81e70c9f: swap_cluster_readahead.cold (STB_LOCAL)
ffffffff8137c420-ffffffff8137c7b8: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:607
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff82065bd3-ffffffff82065c36: swap_cluster_readahead.cold (STB_LOCAL)
ffffffff813f9be0-ffffffff813f9f78: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:622
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff820e5366-ffffffff820e53c8: swap_cluster_readahead.cold (STB_LOCAL)
ffffffff8142cb40-ffffffff8142cec0: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct folio *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct mempolicy *mpol, long unsigned int ilx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:634
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff821c24f2-ffffffff821c255e: swap_cluster_readahead.cold (STB_LOCAL)
ffffffff814662a0-ffffffff814665c2: swap_cluster_readahead (STB_GLOBAL)
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
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010321d80)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffff800010321d80-ffff800010322080: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c053a454)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
c053a454-c053a738: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f7650)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
c0000000003f7650-c0000000003f7a20: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe000222e42)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffe000222e42-ffffffe0002230d0: swap_cluster_readahead (STB_GLOBAL)
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
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127f890)
Location: mm/swap_state.c:498
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff8127f890-ffffffff8127fae7: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812716b0)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff812716b0-ffffffff8127198e: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127d630)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff8127d630-ffffffff8127d90e: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *swap_cluster_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128d1e0)
Location: mm/swap_state.c:539
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff8128d1e0-ffffffff8128d4be: swap_cluster_readahead (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mempolicy *mpol</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int ilx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
</li>
</ul>
</details>
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
