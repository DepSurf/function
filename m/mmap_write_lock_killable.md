# Function: <code>mmap_write_lock_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810057dc)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In kernel/fork.c (ffffffff810a53bc)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810c4cd7)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff81245925)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In mm/util.c (ffffffff812734ae)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81297d35)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8129b79f)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8129f543)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812a1032)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff812b62de)
Location: include/linux/mmap_lock.h:24
Inline: True
```
```
In fs/exec.c (ffffffff8131b6ec)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/aio.c (ffffffff81377890)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff813a7dc6)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813b7183)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff814911b9)
Location: include/linux/mmap_lock.h:24
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e2d4)
Location: include/linux/mmap_lock.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810047fc)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810a0b1c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810c00db)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff81250215)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In mm/util.c (ffffffff8127dc0e)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812a2e3c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812a697c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812aa909)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812ac829)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff812c1232)
Location: include/linux/mmap_lock.h:82
Inline: True
```
```
In fs/exec.c (ffffffff813270ff)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/aio.c (ffffffff813851e4)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff813b96d9)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813c8a0a)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff814ae9a5)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad2ec)
Location: include/linux/mmap_lock.h:82
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8100473c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810a18ac)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810c1ae0)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff81256b71)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/util.c (ffffffff81282dde)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812a869c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812ac92c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812afd46)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812b1b2b)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff812c803e)
Location: include/linux/mmap_lock.h:82
Inline: True
```
```
In fs/exec.c (ffffffff8132d19f)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/aio.c (ffffffff8138bf94)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff813c0839)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813cfa4c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff814b47c5)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189038b)
Location: include/linux/mmap_lock.h:82
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004d6c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810b344c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810d4895)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff81292911)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/util.c (ffffffff812c0ece)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812e9cdc)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812ee07c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812f1596)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812f36fb)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff8130ce16)
Location: include/linux/mmap_lock.h:82
Inline: True
```
```
In fs/exec.c (ffffffff8137aa1f)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/aio.c (ffffffff813d9547)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff814106a9)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff81420e2c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff8150ce75)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192407a)
Location: include/linux/mmap_lock.h:82
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003e4c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810c967c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810ed213)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff812e8305)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/util.c (ffffffff8131dd28)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81349c3c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81351477)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81355252)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813573ad)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff81378aad)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In fs/exec.c (ffffffff813faff3)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
```
```
In fs/aio.c (ffffffff814635ed)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff8148492c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81498ca6)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff8159ed95)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79aab)
Location: include/linux/mmap_lock.h:82
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8100492c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810e6c56)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff8110e633)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff8134efb5)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In mm/util.c (ffffffff81391828)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff813c272c)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813caf2d)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813cf7bd)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813d1998)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff813f63dd)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In fs/exec.c (ffffffff814848f0)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
```
```
In fs/aio.c (ffffffff814f26dd)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff81517e24)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8152cfa2)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff816484c2)
Location: include/linux/mmap_lock.h:82
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810040ec)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a719)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In kernel/fork.c (ffffffff810f260b)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff8111ac17)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff81380175)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In mm/util.c (ffffffff813c41f8)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/memory.c (ffffffff813f175e)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mlock.c (ffffffff813f766c)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813ff173)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81404155)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81406594)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff8142923d)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In fs/exec.c (ffffffff814b94d0)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
```
```
In fs/aio.c (ffffffff81529316)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff81546a4e)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff815497cd)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8154f71e)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81564c99)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff81680a06)
Location: include/linux/mmap_lock.h:111
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810069fc)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In arch/x86/kernel/process_64.c (ffffffff8105186c)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In kernel/fork.c (ffffffff810fb0dc)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff8112476b)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff813a9525)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In mm/util.c (ffffffff813eeda8)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/memory.c (ffffffff8141c43e)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mlock.c (ffffffff8142324c)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142b698)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81430725)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432ca4)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff81462a6d)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In fs/exec.c (ffffffff814ebfd7)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
```
```
In fs/aio.c (ffffffff8155e1e6)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8157be9e)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ea4d)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8158555d)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8159b758)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff816bce25)
Location: include/linux/mmap_lock.h:119
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
