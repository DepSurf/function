# Function: <code>split_huge_pmd_address</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81216700)
Location: mm/huge_memory.c:1666
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff81216700-ffffffff812167ca: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81228cc0)
Location: mm/huge_memory.c:1794
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff81228cc0-ffffffff81228d8a: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812349b0)
Location: mm/huge_memory.c:2116
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812349b0-ffffffff81234a79: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81254380)
Location: mm/huge_memory.c:2268
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff81254380-ffffffff81254492: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81278210)
Location: mm/huge_memory.c:2260
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff81278210-ffffffff812782e8: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128c850)
Location: mm/huge_memory.c:2282
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff8128c850-ffffffff8128c928: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a7530)
Location: mm/huge_memory.c:2340
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812a7530-ffffffff812a7605: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b89d0)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812b89d0-ffffffff812b8aa5: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ed530)
Location: mm/huge_memory.c:2255
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812ed530-ffffffff812ed65b: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f8c50)
Location: mm/huge_memory.c:2279
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812f8c50-ffffffff812f8d7b: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ff1c0)
Location: mm/huge_memory.c:2296
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812ff1c0-ffffffff812ff2c9: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:2224
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff81cc2601-ffffffff81cc261a: split_huge_pmd_address.cold (STB_LOCAL)
ffffffff81348db0-ffffffff81348ed6: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:2244
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff81e74bcf-ffffffff81e74be8: split_huge_pmd_address.cold (STB_LOCAL)
ffffffff813bf210-ffffffff813bf35c: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814419b5)
Location: mm/huge_memory.c:2329
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff814417d0-ffffffff81441827: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81477385)
Location: mm/huge_memory.c:2322
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff814771a0-ffffffff814771f7: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a6b05)
Location: mm/huge_memory.c:2653
Inline: True
Inline callers:
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff814a6920-ffffffff814a6977: split_huge_pmd_address (STB_GLOBAL)
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
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010359088)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffff800010359088-ffff80001035913c: split_huge_pmd_address (STB_GLOBAL)
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
In mm/rmap.c (0)
Location: include/linux/huge_mm.h:338
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c0000000004422b0)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
c0000000004422b0-c00000000044240c: split_huge_pmd_address (STB_GLOBAL)
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
In mm/rmap.c (0)
Location: include/linux/huge_mm.h:338
Inline: True
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
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b0fb0)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812b0fb0-ffffffff812b1085: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a23b0)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812a23b0-ffffffff812a245e: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aedc0)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812aedc0-ffffffff812aee95: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void split_huge_pmd_address(struct vm_area_struct *vma, long unsigned int address, bool freeze, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bf110)
Location: mm/huge_memory.c:2345
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
```
**Symbols:**

```
ffffffff812bf110-ffffffff812bf1e5: split_huge_pmd_address (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
