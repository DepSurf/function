# Function: <code>down_write_killable</code>

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
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8189cd50)
Location: kernel/locking/rwsem.c:63
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/sys.c:SyS_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_munmap
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:SyS_mprotect
  - mm/mremap.c:SyS_mremap
  - mm/madvise.c:SyS_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8189cd50-ffffffff8189cd9f: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff818d1c30)
Location: kernel/locking/rwsem.c:63
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/sys.c:SyS_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_munmap
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:SyS_mremap
  - mm/madvise.c:SyS_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff818d1c30-ffffffff818d1c7f: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81908e00)
Location: kernel/locking/rwsem.c:64
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/sys.c:SyS_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:SyS_mremap
  - mm/madvise.c:SyS_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81908e00-ffffffff81908e4e: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81992f10)
Location: kernel/locking/rwsem.c:81
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/sys.c:SyS_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:SyS_mremap
  - mm/madvise.c:SyS_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81992f10-ffffffff81992f5e: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff819ef4f0)
Location: kernel/locking/rwsem.c:81
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:copy_mm
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff819ef4f0-ffffffff819ef53e: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a2a830)
Location: kernel/locking/rwsem.c:81
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81a2a830-ffffffff81a2a87e: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a9af20)
Location: kernel/locking/rwsem.c:1508
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__do_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81a9af20-ffffffff81a9af74: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81ad2870)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__do_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81ad2870-ffffffff81ad28c4: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81bca990)
Location: kernel/locking/rwsem.c:1539
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:xol_add_vma
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:coredump_wait
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81bca990-ffffffff81bca9e8: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81c43800)
Location: kernel/locking/rwsem.c:1414
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:xol_add_vma
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81c43800-ffffffff81c43858: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81c35630)
Location: kernel/locking/rwsem.c:1414
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81c35630-ffffffff81c35688: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81d53e50)
Location: kernel/locking/rwsem.c:1531
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81d53e50-ffffffff81d53ea8: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81f25c30)
Location: kernel/locking/rwsem.c:1560
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - mm/madvise.c:do_madvise
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81f25c30-ffffffff81f25c8b: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff820d1650)
Location: kernel/locking/rwsem.c:1581
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:xol_add_vma
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - mm/madvise.c:do_madvise
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff820d1650-ffffffff820d16d2: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff821559c0)
Location: kernel/locking/rwsem.c:1581
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:xol_add_vma
  - mm/util.c:vm_mmap_pgoff
  - mm/memory.c:lock_mm_and_find_vma
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - mm/madvise.c:do_madvise
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/aio.c:aio_setup_ring
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff821559c0-ffffffff82155a42: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff82238800)
Location: kernel/locking/rwsem.c:1587
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/events/uprobes.c:xol_add_vma
  - mm/util.c:vm_mmap_pgoff
  - mm/memory.c:lock_mm_and_find_vma
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - mm/madvise.c:do_madvise
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/aio.c:aio_setup_ring
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff82238800-ffffffff82238882: down_write_killable (STB_GLOBAL)
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
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010da4d40)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/arm64/kernel/vdso.c:arch_setup_additional_pages
  - arch/arm64/kernel/vdso.c:aarch32_setup_additional_pages
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__arm64_sys_munlockall
  - mm/mlock.c:__arm64_sys_mlockall
  - mm/mlock.c:__arm64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__arm64_sys_brk
  - mm/mprotect.c:__arm64_sys_mprotect
  - mm/mremap.c:__arm64_sys_mremap
  - mm/madvise.c:__arm64_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffff800010da4d40-ffff800010da4dcc: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0e9cdb4)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/arm/kernel/process.c:arch_setup_additional_pages
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__se_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__se_sys_brk
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mremap.c:__se_sys_mremap
  - mm/madvise.c:__se_sys_madvise
  - fs/exec.c:__do_execve_file
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c0e9cdb4-c0e9ce30: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c000000000ee73b0)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/powerpc/kernel/vdso.c:arch_setup_additional_pages
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__se_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__se_sys_brk
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mremap.c:__se_sys_mremap
  - mm/madvise.c:__se_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c000000000ee73b0-c000000000ee7458: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe0008c7b92)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__se_sys_prctl
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__se_sys_brk
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mremap.c:__se_sys_mremap
  - mm/madvise.c:__se_sys_madvise
  - fs/exec.c:__do_execve_file
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe0008c7b92-ffffffe0008c7bf0: down_write_killable (STB_GLOBAL)
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
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a716e0)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__do_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81a716e0-ffffffff81a71734: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a2dad0)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__do_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81a2dad0-ffffffff81a2db24: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81addaf0)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__do_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81addaf0-ffffffff81addb44: down_write_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81ae9fc0)
Location: kernel/locking/rwsem.c:1542
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/events/uprobes.c:__create_xol_area
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/madvise.c:__do_sys_madvise
  - fs/exec.c:setup_arg_pages
  - fs/readdir.c:iterate_dir
  - fs/aio.c:aio_setup_ring
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/configfs/dir.c:configfs_rmdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81ae9fc0-ffffffff81aea000: down_write_killable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
