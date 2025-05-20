# Function: <code>get_gate_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004b40)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:298
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81004b40-ffffffff81004b75: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004cf8)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:298
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81004cb0-ffffffff81004ce5: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004d68)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:298
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81004d20-ffffffff81004d55: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004bf8)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:300
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81004bb0-ffffffff81004be5: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004e48)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:306
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81004e00-ffffffff81004e35: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005595)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:302
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005550-ffffffff81005585: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005495)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:295
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005450-ffffffff81005485: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005545)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005500-ffffffff81005535: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055c5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005580-ffffffff810055b5: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81006445)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:vma_dump_size
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:vma_dump_size
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81006400-ffffffff81006435: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005645)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:vma_dump_size
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005600-ffffffff81005634: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055a5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:vma_dump_size
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005560-ffffffff81005594: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005be5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:317
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:vma_dump_size
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005ba0-ffffffff81005bd4: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004df5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:317
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:vma_dump_size
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81004da0-ffffffff81004de4: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005895)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:317
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/vmscan.c:should_skip_vma
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:vma_dump_size
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005830-ffffffff81005874: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005045)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:317
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/vmscan.c:should_skip_vma
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:vma_dump_size
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81004fe0-ffffffff81005026: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81007955)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:317
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/vmscan.c:should_skip_vma
  - mm/gup.c:get_gate_page
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:vma_dump_size
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff810078f0-ffffffff81007936: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030b528)
Location: arch/arm/kernel/process.c:342
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
c030b528-c030b548: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/mm.h:2745
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2745
Inline: True
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
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055c5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005580-ffffffff810055b5: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81003ca5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81003c60-ffffffff81003c95: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005585)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81005540-ffffffff81005575: get_gate_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *get_gate_vma(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810056e5)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:316
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:mmap_region
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff810056a0-ffffffff810056d5: get_gate_vma (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
