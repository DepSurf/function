# Function: <code>free_pgtables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd110)
Location: mm/memory.c:529
Inline: False
Direct callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff811bd110-ffffffff811bd222: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d7ee0)
Location: mm/memory.c:541
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff811d7ee0-ffffffff811d7ffc: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7bb0)
Location: mm/memory.c:543
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff811e7bb0-ffffffff811e7ccc: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2d60)
Location: mm/memory.c:608
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff811f2d60-ffffffff811f2e6a: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209ec0)
Location: mm/memory.c:610
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff81209ec0-ffffffff81209fca: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122ace0)
Location: mm/memory.c:625
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff8122ace0-ffffffff8122ade9: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123e0a0)
Location: mm/memory.c:368
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff8123e0a0-ffffffff8123e1aa: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f920)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff8124f920-ffffffff8124fa07: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125dec0)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff8125dec0-ffffffff8125dfa7: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128dc60)
Location: mm/memory.c:388
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff8128dc60-ffffffff8128dd47: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812988d0)
Location: mm/memory.c:390
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff812988d0-ffffffff812989c4: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129dff0)
Location: mm/memory.c:402
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff8129dff0-ffffffff8129e0e2: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812df230)
Location: mm/memory.c:401
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff812df230-ffffffff812df322: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133f760)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff8133f760-ffffffff8133f841: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct maple_tree *mt, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b7610)
Location: mm/memory.c:349
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff813b7610-ffffffff813b776e: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct maple_tree *mt, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling, bool mm_wr_locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ec320)
Location: mm/memory.c:364
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff813ec320-ffffffff813ec504: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct ma_state *mas, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling, bool mm_wr_locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417b90)
Location: mm/memory.c:362
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff81417b90-ffffffff81417d47: free_pgtables (STB_GLOBAL)
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
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f58e0)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffff8000102f58e0-ffff8000102f5a10: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0517708)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
c0517708-c05177cc: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bcd20)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
c0000000003bcd20-c0000000003bcf20: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000206cea)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffe000206cea-ffffffe000206ddc: free_pgtables (STB_GLOBAL)
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
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256510)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff81256510-ffffffff812565f7: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81248f50)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff81248f50-ffffffff81249037: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812542b0)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff812542b0-ffffffff81254397: free_pgtables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_pgtables(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int floor, long unsigned int ceiling);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263d40)
Location: mm/memory.c:370
Inline: False
Direct callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
```
**Symbols:**

```
ffffffff81263d40-ffffffff81263e27: free_pgtables (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct maple_tree *mt</code>
</li>
<li>
<b>Param reordered. </b>
<code>tlb, vma, floor, ceiling</code> ➡️ <code>tlb, mt, vma, floor, ceiling</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool mm_wr_locked</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ma_state *mas</code>
</li>
<li>
<b>Param removed. </b>
<code>struct maple_tree *mt</code>
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
