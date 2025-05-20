# Function: <code>handle_mm_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int handle_mm_fault(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bebd0)
Location: mm/memory.c:3432
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:fixup_user_fault
  - mm/ksm.c:break_ksm
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811bebd0-ffffffff811c03ed: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811daa40)
Location: mm/memory.c:3619
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811daa40-ffffffff811dbdf8: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ea5b0)
Location: mm/memory.c:3661
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811ea5b0-ffffffff811eb906: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f6640)
Location: mm/memory.c:3914
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811f6640-ffffffff811f6837: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120eae0)
Location: mm/memory.c:4090
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_clear
  - mm/hmm.c:hmm_vma_walk_hole
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8120eae0-ffffffff8120ecc5: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81230270)
Location: mm/memory.c:4135
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81230270-ffffffff8123047d: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81242c20)
Location: mm/memory.c:3925
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81242c20-ffffffff81242e2d: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3974
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8125745a-ffffffff81257480: handle_mm_fault.cold (STB_LOCAL)
ffffffff81254ac0-ffffffff81254ca3: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263020)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81263020-ffffffff81263214: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81294e00)
Location: mm/memory.c:4380
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81294e00-ffffffff81294fe6: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129f680)
Location: mm/memory.c:4601
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8129f680-ffffffff8129f929: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a4680)
Location: mm/memory.c:4628
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_fault
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff812a4680-ffffffff812a4938: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e5930)
Location: mm/memory.c:4774
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_fault
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
**Symbols:**

```
ffffffff812e5930-ffffffff812e5be1: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81347c40)
Location: mm/memory.c:5117
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
**Symbols:**

```
ffffffff81347c40-ffffffff81347ed8: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0030)
Location: mm/memory.c:5192
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
**Symbols:**

```
ffffffff813c0030-ffffffff813c0358: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f4cf0)
Location: mm/memory.c:5202
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
**Symbols:**

```
ffffffff813f4cf0-ffffffff813f504f: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81421360)
Location: mm/memory.c:5439
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
**Symbols:**

```
ffffffff81421360-ffffffff814216d7: handle_mm_fault (STB_GLOBAL)
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
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fa2e8)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/arm64/mm/fault.c:do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
```
**Symbols:**

```
ffff8000102fa2e8-ffff8000102fa45c: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051bc0c)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/arm/mm/fault.c:do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
```
**Symbols:**

```
c051bc0c-c051bff8: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c4430)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/copro_fault.c:copro_handle_mm_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
```
**Symbols:**

```
c0000000003c4430-c0000000003c45fc: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000209aa0)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/riscv/mm/fault.c:do_page_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
```
**Symbols:**

```
ffffffe000209aa0-ffffffe000209c18: handle_mm_fault (STB_GLOBAL)
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
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b670)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8125b670-ffffffff8125b864: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124dc50)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8124dc50-ffffffff8124de2e: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259410)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81259410-ffffffff81259604: handle_mm_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct *vma, long unsigned int address, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81268e10)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/ksm.c:break_ksm
  - mm/hmm.c:hmm_vma_walk_hole_
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81268e10-ffffffff8126900e: handle_mm_fault (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, address, flags</code> ➡️ <code>vma, address, flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs *regs</code>
</li>
</ul>
</details>
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
