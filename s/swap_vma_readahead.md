# Function: <code>swap_vma_readahead</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812483eb)
Location: mm/swap_state.c:732
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125c9bb)
Location: mm/swap_state.c:694
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81277b9f)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128768f)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b97c0)
Location: mm/swap_state.c:740
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff812b97c0-ffffffff812b99eb: swap_vma_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c5220)
Location: mm/swap_state.c:832
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff812c5220-ffffffff812c5451: swap_vma_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cbec0)
Location: mm/swap_state.c:801
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff812cbec0-ffffffff812cc10b: swap_vma_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:788
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff81311090-ffffffff813112fc: swap_vma_readahead (STB_LOCAL)
ffffffff81cbea5b-ffffffff81cbea94: swap_vma_readahead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:801
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff8137c070-ffffffff8137c37f: swap_vma_readahead (STB_LOCAL)
ffffffff81e70be3-ffffffff81e70c27: swap_vma_readahead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:785
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff813f9810-ffffffff813f9b1f: swap_vma_readahead (STB_LOCAL)
ffffffff82065b7a-ffffffff82065bbe: swap_vma_readahead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *swap_vma_readahead(swp_entry_t fentry, gfp_t gfp_mask, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:783
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff8142c5c0-ffffffff8142ca80: swap_vma_readahead (STB_LOCAL)
ffffffff820e531b-ffffffff820e5351: swap_vma_readahead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct folio *swap_vma_readahead(swp_entry_t targ_entry, gfp_t gfp_mask, struct mempolicy *mpol, long unsigned int targ_ilx, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:799
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff81465cf0-ffffffff814661a7: swap_vma_readahead (STB_LOCAL)
ffffffff821c2493-ffffffff821c24de: swap_vma_readahead.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010322204)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c053a890)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f7c18)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe000223222)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127fc59)
Location: mm/swap_state.c:680
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81271ad2)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127da7f)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128d62f)
Location: mm/swap_state.c:722
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
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
<code>swp_entry_t targ_entry</code>
</li>
<li>
<b>Param added. </b>
<code>struct mempolicy *mpol</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int targ_ilx</code>
</li>
<li>
<b>Param removed. </b>
<code>swp_entry_t fentry</code>
</li>
<li>
<b>Param reordered. </b>
<code>fentry, gfp_mask, vmf</code> ➡️ <code>targ_entry, gfp_mask, mpol, targ_ilx, vmf</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
</li>
</ul>
</details>
</li>
</ul>
