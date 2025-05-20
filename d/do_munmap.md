# Function: <code>do_munmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c6450)
Location: mm/mmap.c:2532
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:do_brk
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:mmap_region
  - mm/mremap.c:move_vma
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:SyS_shmdt
```
**Symbols:**

```
ffffffff811c6450-ffffffff811c68d0: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e1ee0)
Location: mm/mmap.c:2429
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mmap.c:do_brk
  - mm/mmap.c:SyS_munmap
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:SyS_shmdt
```
**Symbols:**

```
ffffffff811e1ee0-ffffffff811e2352: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f1ed0)
Location: mm/mmap.c:2582
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mmap.c:do_brk
  - mm/mmap.c:SyS_munmap
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:SyS_shmdt
```
**Symbols:**

```
ffffffff811f1ed0-ffffffff811f2322: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fce50)
Location: mm/mmap.c:2617
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:SyS_shmdt
```
**Symbols:**

```
ffffffff811fce50-ffffffff811fd2e6: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812153f0)
Location: mm/mmap.c:2635
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:SyS_shmdt
```
**Symbols:**

```
ffffffff812153f0-ffffffff81215846: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81236220)
Location: mm/mmap.c:2690
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff81236220-ffffffff8123665f: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124ab50)
Location: mm/mmap.c:2832
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff8124a020-ffffffff8124a033: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125cfc9)
Location: mm/mmap.c:2838
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff8125c320-ffffffff8125c333: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126b799)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff8126aa80-ffffffff8126aa93: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129b5a1)
Location: mm/mmap.c:2853
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_checked
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff8129cca0-ffffffff8129ccb3: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a67df)
Location: mm/mmap.c:2916
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:remap_oldmem_pfn_checked
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff812a8050-ffffffff812a8063: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ac7a9)
Location: mm/mmap.c:2920
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff812aba70-ffffffff812aba83: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812edef9)
Location: mm/mmap.c:2892
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff812ed160-ffffffff812ed173: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351322)
Location: mm/mmap.c:2893
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff813504d0-ffffffff813504f2: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c9db0)
Location: mm/mmap.c:2511
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff813c9db0-ffffffff813c9e40: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fe260)
Location: mm/mmap.c:2632
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
```
**Symbols:**

```
ffffffff813fe260-ffffffff813fe2e2: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142a640)
Location: mm/mmap.c:2714
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
```
**Symbols:**

```
ffffffff8142a640-ffffffff8142a6c1: do_munmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010302f38)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffff800010302168-ffff8000103021b8: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05215b8)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
c0520848-c0520874: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cf7b0)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
c0000000003ce580-c0000000003ce598: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fc02)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffe00020f138-ffffffe00020f17c: do_munmap (STB_GLOBAL)
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
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263de9)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff812630d0-ffffffff812630e3: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81256209)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff812554f0-ffffffff81255503: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261b89)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff81260e70-ffffffff81260e83: do_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_munmap(struct mm_struct *mm, long unsigned int start, size_t len, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81271549)
Location: mm/mmap.c:2843
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/proc/vmcore.c:mmap_vmcore
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff81270840-ffffffff81270853: do_munmap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head *uf</code>
</li>
</ul>
</details>
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
