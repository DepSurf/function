# Function: <code>unmap_single_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bdcd0)
Location: mm/memory.c:1272
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:zap_page_range
```
**Symbols:**

```
ffffffff811bdcd0-ffffffff811bddb0: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d94f0)
Location: mm/memory.c:1305
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff811d94f0-ffffffff811d95d0: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e8900)
Location: mm/memory.c:1301
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff811e8900-ffffffff811e89e0: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f3b60)
Location: mm/memory.c:1424
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff811f3b60-ffffffff811f3c44: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120b820)
Location: mm/memory.c:1515
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff8120b820-ffffffff8120b904: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122c540)
Location: mm/memory.c:1527
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff8122c540-ffffffff8122c620: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123fa10)
Location: mm/memory.c:1269
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff8123fa10-ffffffff8123faf0: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81251b20)
Location: mm/memory.c:1238
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff81251b20-ffffffff81251c01: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812600d0)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff812600d0-ffffffff812601b1: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812906a0)
Location: mm/memory.c:1271
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff812906a0-ffffffff81290781: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129b130)
Location: mm/memory.c:1445
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff8129b130-ffffffff8129b211: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0450)
Location: mm/memory.c:1463
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff812a0450-ffffffff812a0535: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e13e0)
Location: mm/memory.c:1558
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff812e13e0-ffffffff812e14c5: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81341ec0)
Location: mm/memory.c:1644
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff81341ec0-ffffffff81341fd7: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b9df0)
Location: mm/memory.c:1602
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff813b9df0-ffffffff813b9ec0: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details, bool mm_wr_locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eeb10)
Location: mm/memory.c:1647
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff813eeb10-ffffffff813eebfa: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details, bool mm_wr_locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141a5c0)
Location: mm/memory.c:1674
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff8141a5c0-ffffffff8141a6aa: unmap_single_vma (STB_LOCAL)
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
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f7408)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffff8000102f7408-ffff8000102f74f0: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519434)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
c0519434-c05194cc: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c00d0)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
c0000000003c00d0-c0000000003c0230: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207a82)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffe000207a82-ffffffe000207b38: unmap_single_vma (STB_LOCAL)
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
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258720)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff81258720-ffffffff81258801: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124abe0)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff8124abe0-ffffffff8124acc1: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812564c0)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff812564c0-ffffffff812565a1: unmap_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unmap_single_vma(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265f60)
Location: mm/memory.c:1243
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
```
**Symbols:**

```
ffffffff81265f60-ffffffff81266041: unmap_single_vma (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
