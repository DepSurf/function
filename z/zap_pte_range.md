# Function: <code>zap_pte_range</code>

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
In mm/memory.c (ffffffff811bd5c1)
Location: mm/memory.c:1073
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
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
In mm/memory.c (ffffffff811d8cf4)
Location: mm/memory.c:1109
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
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
In mm/memory.c (ffffffff811e81c4)
Location: mm/memory.c:1111
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
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
In mm/memory.c (ffffffff811f344c)
Location: mm/memory.c:1211
Inline: True
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
In mm/memory.c (ffffffff8120aba4)
Location: mm/memory.c:1279
Inline: True
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
In mm/memory.c (ffffffff8122bd65)
Location: mm/memory.c:1293
Inline: True
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
In mm/memory.c (ffffffff8123f177)
Location: mm/memory.c:1035
Inline: True
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
In mm/memory.c (ffffffff81250a60)
Location: mm/memory.c:1004
Inline: True
```
**Symbols:**

```
ffffffff81250a60-ffffffff8125124b: zap_pte_range.isra.0 (STB_LOCAL)
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
In mm/memory.c (ffffffff8125f010)
Location: mm/memory.c:1004
Inline: True
```
**Symbols:**

```
ffffffff8125f010-ffffffff8125f7ff: zap_pte_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128f420)
Location: mm/memory.c:1032
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff8128f420-ffffffff8128fcaa: zap_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81299f30)
Location: mm/memory.c:1206
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff81299f30-ffffffff8129a722: zap_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129f150)
Location: mm/memory.c:1213
Inline: False
```
**Symbols:**

```
ffffffff8129f150-ffffffff8129f8d3: zap_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e03f0)
Location: mm/memory.c:1304
Inline: False
```
**Symbols:**

```
ffffffff812e03f0-ffffffff812e0c3a: zap_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1394
Inline: False
```
**Symbols:**

```
ffffffff81340a00-ffffffff8134152a: zap_pte_range (STB_LOCAL)
ffffffff81e6df48-ffffffff81e6dfcb: zap_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1342
Inline: False
```
**Symbols:**

```
ffffffff813b89a0-ffffffff813b945b: zap_pte_range (STB_LOCAL)
ffffffff82063f50-ffffffff82063fdb: zap_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1394
Inline: False
```
**Symbols:**

```
ffffffff813ed620-ffffffff813ee083: zap_pte_range (STB_LOCAL)
ffffffff820e361a-ffffffff820e36b1: zap_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1414
Inline: False
```
**Symbols:**

```
ffffffff81418bf0-ffffffff814196d2: zap_pte_range (STB_LOCAL)
ffffffff821c006f-ffffffff821c00fa: zap_pte_range.cold (STB_LOCAL)
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
In mm/memory.c (ffff8000102f6cc4)
Location: mm/memory.c:1004
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
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
In mm/memory.c (c0518d78)
Location: mm/memory.c:1004
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003be770)
Location: mm/memory.c:1004
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
c0000000003be770-c0000000003bf364: zap_pte_range (STB_LOCAL)
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
In mm/memory.c (ffffffe0002074ce)
Location: mm/memory.c:1004
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
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
In mm/memory.c (ffffffff81257660)
Location: mm/memory.c:1004
Inline: True
```
**Symbols:**

```
ffffffff81257660-ffffffff81257e4f: zap_pte_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int zap_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81249f40)
Location: mm/memory.c:1004
Inline: False
```
**Symbols:**

```
ffffffff81249f40-ffffffff8124a6a6: zap_pte_range (STB_LOCAL)
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
In mm/memory.c (ffffffff81255400)
Location: mm/memory.c:1004
Inline: True
```
**Symbols:**

```
ffffffff81255400-ffffffff81255bef: zap_pte_range.isra.0 (STB_LOCAL)
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
In mm/memory.c (ffffffff81264eb0)
Location: mm/memory.c:1004
Inline: True
```
**Symbols:**

```
ffffffff81264eb0-ffffffff81265675: zap_pte_range.isra.0 (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
