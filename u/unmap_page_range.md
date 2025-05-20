# Function: <code>unmap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd530)
Location: mm/memory.c:1248
Inline: False
Direct callers:
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff811bd530-ffffffff811bdcc5: unmap_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d8b80)
Location: mm/memory.c:1284
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff811d8b80-ffffffff811d94e3: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e8050)
Location: mm/memory.c:1280
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff811e8050-ffffffff811e88f6: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f31f0)
Location: mm/memory.c:1403
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff811f31f0-ffffffff811f3b5f: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120ab30)
Location: mm/memory.c:1494
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff8120ab30-ffffffff8120b81f: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122b9e0)
Location: mm/memory.c:1506
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff8122b9e0-ffffffff8122c534: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123edb0)
Location: mm/memory.c:1248
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff8123edb0-ffffffff8123fa09: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81251680)
Location: mm/memory.c:1217
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81251680-ffffffff81251b1c: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125fc30)
Location: mm/memory.c:1222
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff8125fc30-ffffffff812600cc: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812900c0)
Location: mm/memory.c:1250
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff812900c0-ffffffff81290696: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129ab50)
Location: mm/memory.c:1424
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff8129ab50-ffffffff8129b126: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a00a0)
Location: mm/memory.c:1442
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff812a00a0-ffffffff812a0443: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1537
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81cbc3b0-ffffffff81cbc413: unmap_page_range.cold (STB_LOCAL)
ffffffff812e1010-ffffffff812e13de: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1623
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81e6dfcb-ffffffff81e6e039: unmap_page_range.cold (STB_LOCAL)
ffffffff81341990-ffffffff81341ebf: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1581
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff82063fdb-ffffffff8206403b: unmap_page_range.cold (STB_LOCAL)
ffffffff813b98c0-ffffffff813b9ddd: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1626
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff820e36b1-ffffffff820e3712: unmap_page_range.cold (STB_LOCAL)
ffffffff813ee5e0-ffffffff813eeaf4: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff821c00fa-ffffffff821c015b: unmap_page_range.cold (STB_LOCAL)
ffffffff8141a0c0-ffffffff8141a5ad: unmap_page_range (STB_GLOBAL)
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
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f6a38)
Location: mm/memory.c:1222
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffff8000102f6a38-ffff8000102f7408: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0518c9c)
Location: mm/memory.c:1222
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
c0518c9c-c0519434: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bf9e0)
Location: mm/memory.c:1222
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
c0000000003bf9e0-c0000000003c00c8: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207476)
Location: mm/memory.c:1222
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffe000207476-ffffffe000207a82: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258280)
Location: mm/memory.c:1222
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81258280-ffffffff8125871c: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124a7c0)
Location: mm/memory.c:1222
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff8124a7c0-ffffffff8124abd8: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256020)
Location: mm/memory.c:1222
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81256020-ffffffff812564bc: unmap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void unmap_page_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265ac0)
Location: mm/memory.c:1222
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:unmap_single_vma
```
**Symbols:**

```
ffffffff81265ac0-ffffffff81265f53: unmap_page_range (STB_GLOBAL)
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
