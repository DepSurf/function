# Function: <code>unuse_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d43eb)
Location: mm/swapfile.c:1140
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f21ee)
Location: mm/swapfile.c:1129
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81202be6)
Location: mm/swapfile.c:1149
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120dc92)
Location: mm/swapfile.c:1561
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81228ebb)
Location: mm/swapfile.c:1773
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124a1c6)
Location: mm/swapfile.c:1773
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff8125e806)
Location: mm/swapfile.c:1745
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81279600)
Location: mm/swapfile.c:1853
Inline: True
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81279600-ffffffff81279948: unuse_pte.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812890e0)
Location: mm/swapfile.c:1853
Inline: True
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812890e0-ffffffff81289428: unuse_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bbb30)
Location: mm/swapfile.c:1890
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812bbb30-ffffffff812bbdf6: unuse_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c75e0)
Location: mm/swapfile.c:1911
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812c75e0-ffffffff812c7894: unuse_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cdf20)
Location: mm/swapfile.c:1911
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812cdf20-ffffffff812ce20a: unuse_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813133a0)
Location: mm/swapfile.c:1898
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff813133a0-ffffffff81313687: unuse_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137e740)
Location: mm/swapfile.c:1773
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8137e740-ffffffff8137ecdf: unuse_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fd110)
Location: mm/swapfile.c:1760
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff813fd110-ffffffff813fd7b0: unuse_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81430410)
Location: mm/swapfile.c:1742
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81430410-ffffffff81430a65: unuse_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unuse_pte(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, swp_entry_t entry, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81468dc0)
Location: mm/swapfile.c:1742
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81468dc0-ffffffff81469256: unuse_pte (STB_LOCAL)
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
In mm/swapfile.c (ffff800010325e78)
Location: mm/swapfile.c:1853
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
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
In mm/swapfile.c (c053d724)
Location: mm/swapfile.c:1853
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (c0000000003fc2fc)
Location: mm/swapfile.c:1853
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
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
In mm/swapfile.c (ffffffe0002261bc)
Location: mm/swapfile.c:1853
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
</details>
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
In mm/swapfile.c (ffffffff812816c0)
Location: mm/swapfile.c:1853
Inline: True
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812816c0-ffffffff81281a08: unuse_pte.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81274d83)
Location: mm/swapfile.c:1853
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
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
In mm/swapfile.c (ffffffff8127f4d0)
Location: mm/swapfile.c:1853
Inline: True
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8127f4d0-ffffffff8127f818: unuse_pte.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8128f1a0)
Location: mm/swapfile.c:1853
Inline: True
Direct callers:
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8128f1a0-ffffffff8128f4f1: unuse_pte.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
