# Function: <code>get_user_pages_remote</code>

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
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages, struct vm_area_struct **vmas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5da0)
Location: mm/gup.c:961
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff811d5da0-ffffffff811d5df6: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e5d60)
Location: mm/gup.c:964
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff811e5d60-ffffffff811e5f17: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f03d0)
Location: mm/gup.c:1045
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff811f03d0-ffffffff811f0579: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81207810)
Location: mm/gup.c:1070
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff81207810-ffffffff812079b9: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812283c0)
Location: mm/gup.c:1076
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff812283c0-ffffffff81228569: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123bbe0)
Location: mm/gup.c:1101
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff8123bbe0-ffffffff8123bd89: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124cf70)
Location: mm/gup.c:1156
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff8124cf70-ffffffff8124d19f: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125b4a0)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff8125b4a0-ffffffff8125b6cf: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a800)
Location: mm/gup.c:1924
Inline: False
Direct callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff8128a800-ffffffff8128a82b: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294470)
Location: mm/gup.c:1788
Inline: False
Direct callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff81294470-ffffffff812944d8: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81299ec0)
Location: mm/gup.c:1854
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff81299ec0-ffffffff81299f28: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da860)
Location: mm/gup.c:1942
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - mm/rmap.c:make_device_exclusive_range
  - fs/exec.c:get_arg_page
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff812da860-ffffffff812da898: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133a310)
Location: mm/gup.c:2131
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - mm/rmap.c:make_device_exclusive_range
  - fs/exec.c:get_arg_page
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff8133a310-ffffffff8133a37e: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1aa0)
Location: mm/gup.c:2176
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - mm/rmap.c:make_device_exclusive_range
  - fs/exec.c:get_arg_page
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff813b1aa0-ffffffff813b1b1b: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e56e0)
Location: mm/gup.c:2320
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - mm/rmap.c:make_device_exclusive_range
  - fs/exec.c:get_arg_page
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff813e56e0-ffffffff813e5aa2: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81410090)
Location: mm/gup.c:2338
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - mm/rmap.c:make_device_exclusive_range
  - fs/exec.c:get_arg_page
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff81410090-ffffffff81410543: get_user_pages_remote (STB_GLOBAL)
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
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2888)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffff8000102f2888-ffff8000102f2ad8: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0514bc0)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - fs/exec.c:copy_strings
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
c0514bc0-c0514e60: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b8f90)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
c0000000003b8f90-c0000000003b9270: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000204e36)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/exec.c:copy_strings
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffe000204e36-ffffffe000204fd6: get_user_pages_remote (STB_GLOBAL)
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
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81253af0)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
```
**Symbols:**

```
ffffffff81253af0-ffffffff81253d1f: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246740)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff81246740-ffffffff8124696f: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251890)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff81251890-ffffffff81251abf: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81261240)
Location: mm/gup.c:1159
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - mm/memory.c:__access_remote_vm
  - security/tomoyo/domain.c:tomoyo_dump_page
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff81261240-ffffffff8126146f: get_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param added. </b>
<code>int *locked</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, write, force, pages, vmas</code> ➡️ <code>tsk, mm, start, nr_pages, gup_flags, pages, vmas, locked</code>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct **vmas</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, locked</code>
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
