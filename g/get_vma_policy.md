# Function: <code>get_vma_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0420)
Location: mm/mempolicy.c:1578
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:mpol_misplaced
Direct callers:
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:mpol_misplaced
```
**Symbols:**

```
ffffffff811e0420-ffffffff811e0446: get_vma_policy.part.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8120166d)
Location: mm/mempolicy.c:1610
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
```
**Symbols:**

```
ffffffff811fe700-ffffffff811fe726: get_vma_policy.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8121315d)
Location: mm/mempolicy.c:1612
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
```
**Symbols:**

```
ffffffff8120f440-ffffffff8120f466: get_vma_policy.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8121e47d)
Location: mm/mempolicy.c:1537
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff8121ad80-ffffffff8121ada7: get_vma_policy.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8123969b)
Location: mm/mempolicy.c:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff81235fa0-ffffffff81235fc7: get_vma_policy.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8125cc6d)
Location: mm/mempolicy.c:1651
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff81258fb0-ffffffff81258fd7: get_vma_policy.part.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8127154d)
Location: mm/mempolicy.c:1691
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff8126d3a0-ffffffff8126d3c7: get_vma_policy.part.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_vma_policy(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8128cb60)
Location: mm/mempolicy.c:1737
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81288760-ffffffff81288786: get_vma_policy.part.0 (STB_LOCAL)
ffffffff8128bbf0-ffffffff8128bc0c: get_vma_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8129c790)
Location: mm/mempolicy.c:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff812982d0-ffffffff812982f6: get_vma_policy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d03e0)
Location: mm/mempolicy.c:1836
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dbf00)
Location: mm/mempolicy.c:1812
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3770)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132a99f)
Location: mm/mempolicy.c:1711
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a350)
Location: mm/mempolicy.c:1775
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a370)
Location: mm/mempolicy.c:1790
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144d910)
Location: mm/mempolicy.c:1801
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_vma_policy(struct vm_area_struct *vma, long unsigned int addr, int order, long unsigned int *ilx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff814852f4)
Location: mm/mempolicy.c:1770
Inline: True
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff821c3b46-ffffffff821c3b8d: get_vma_policy.cold (STB_LOCAL)
ffffffff81485240-ffffffff81485398: get_vma_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffff80001033b724)
Location: mm/mempolicy.c:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffff800010337eb0-ffff800010337ed8: get_vma_policy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (c000000000416498)
Location: mm/mempolicy.c:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
c0000000004116b0-c0000000004116d4: get_vma_policy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81294d70)
Location: mm/mempolicy.c:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff812908b0-ffffffff812908d6: get_vma_policy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81286980)
Location: mm/mempolicy.c:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff81282530-ffffffff81282556: get_vma_policy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81292b80)
Location: mm/mempolicy.c:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff8128e6c0-ffffffff8128e6e6: get_vma_policy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812a2970)
Location: mm/mempolicy.c:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
Direct callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
```
**Symbols:**

```
ffffffff8129e5c0-ffffffff8129e5e6: get_vma_policy.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
