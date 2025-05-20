# Function: <code>do_huge_pmd_numa_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_huge_pmd_numa_page(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, pmd_t pmd, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f6360)
Location: mm/huge_memory.c:1328
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811f6360-ffffffff811f6765: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_huge_pmd_numa_page(struct fault_env *fe, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81215120)
Location: mm/huge_memory.c:1128
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff81215120-ffffffff812155bc: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81227730)
Location: mm/huge_memory.c:1216
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff81227730-ffffffff81227c36: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81233910)
Location: mm/huge_memory.c:1419
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81233910-ffffffff81233e2a: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81251220)
Location: mm/huge_memory.c:1462
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81251220-ffffffff812518ca: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812756f0)
Location: mm/huge_memory.c:1460
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812756f0-ffffffff81275e01: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128a650)
Location: mm/huge_memory.c:1472
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8128a650-ffffffff8128ac69: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a5270)
Location: mm/huge_memory.c:1530
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812a5270-ffffffff812a5885: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b6730)
Location: mm/huge_memory.c:1535
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812b6730-ffffffff812b6d45: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812eb860)
Location: mm/huge_memory.c:1394
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812eb860-ffffffff812ebeaa: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f6910)
Location: mm/huge_memory.c:1415
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812f6910-ffffffff812f6f1b: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fccc0)
Location: mm/huge_memory.c:1421
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812fccc0-ffffffff812fd2ca: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81346b40)
Location: mm/huge_memory.c:1424
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81346b40-ffffffff81346f82: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bce60)
Location: mm/huge_memory.c:1429
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff813bce60-ffffffff813bd2c1: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143f4e0)
Location: mm/huge_memory.c:1509
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8143f4e0-ffffffff8143f9e4: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81474d20)
Location: mm/huge_memory.c:1493
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81474d20-ffffffff81475224: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a42d0)
Location: mm/huge_memory.c:1711
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff814a42d0-ffffffff814a46bd: do_huge_pmd_numa_page (STB_GLOBAL)
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
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103573f0)
Location: mm/huge_memory.c:1535
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffff8000103573f0-ffff800010357ad0: do_huge_pmd_numa_page (STB_GLOBAL)
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
In mm/memory.c (0)
Location: include/linux/huge_mm.h:371
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043f440)
Location: mm/huge_memory.c:1535
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
c00000000043f440-c00000000043fcf4: do_huge_pmd_numa_page (STB_GLOBAL)
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
In mm/memory.c (0)
Location: include/linux/huge_mm.h:371
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
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aed10)
Location: mm/huge_memory.c:1535
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812aed10-ffffffff812af325: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a0230)
Location: mm/huge_memory.c:1535
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812a0230-ffffffff812a081f: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812acb20)
Location: mm/huge_memory.c:1535
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812acb20-ffffffff812ad135: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_numa_page(struct vm_fault *vmf, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bcea0)
Location: mm/huge_memory.c:1535
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812bcea0-ffffffff812bd4c0: do_huge_pmd_numa_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fault_env *fe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t *pmdp</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, addr, pmd, pmdp</code> ➡️ <code>fe, pmd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env *fe</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pmd_t pmd</code>
</li>
</ul>
</details>
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
