# Function: <code>mmap_read_lock_killable</code>

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
In mm/gup.c (ffffffff81289e0f)
Location: include/linux/mmap_lock.h:49
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
```
```
In mm/memory.c (ffffffff812951fd)
Location: include/linux/mmap_lock.h:49
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In fs/proc/task_mmu.c (ffffffff813b681c)
Location: include/linux/mmap_lock.h:49
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813bf455)
Location: include/linux/mmap_lock.h:49
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In mm/gup.c (ffffffff81293af6)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
```
```
In mm/memory.c (ffffffff812a0066)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In fs/binfmt_elf.c (ffffffff813b0987)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3487)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff813c8783)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d1264)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In kernel/bpf/task_iter.c (ffffffff8121bff1)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/gup.c (ffffffff81299496)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
```
```
In mm/memory.c (ffffffff812a59a6)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In fs/binfmt_elf.c (ffffffff813b7acc)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba477)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff813cf7b7)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d8164)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In kernel/bpf/task_iter.c (ffffffff81252eed)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/oom_kill.c (ffffffff812a3211)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/gup.c (ffffffff812d9de0)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
```
```
In mm/memory.c (ffffffff812e6e96)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In fs/binfmt_elf.c (ffffffff814077c3)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a179)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff81420b97)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814298a4)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In kernel/bpf/task_iter.c (ffffffff8129b07d)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/oom_kill.c (ffffffff812fb0ce)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/gup.c (ffffffff81339b12)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
```
```
In mm/memory.c (ffffffff8134802e)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In fs/exec.c (ffffffff813fa7c0)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
```
In fs/binfmt_elf.c (ffffffff8147c4e4)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8147ee8a)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff814989de)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814a2cf7)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In kernel/bpf/task_iter.c (ffffffff812f73a7)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/oom_kill.c (ffffffff8136441e)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/gup.c (ffffffff813b1441)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
```
```
In mm/memory.c (ffffffff813c04cf)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In fs/exec.c (ffffffff81483839)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
```
In fs/binfmt_elf.c (ffffffff8150f194)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81511e0d)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff8152cc99)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81537eea)
Location: include/linux/mmap_lock.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In kernel/bpf/task_iter.c (ffffffff8132527a)
Location: include/linux/mmap_lock.h:152
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/oom_kill.c (ffffffff813968ed)
Location: include/linux/mmap_lock.h:152
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/gup.c (ffffffff813e5e58)
Location: include/linux/mmap_lock.h:152
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
```
```
In mm/memory.c (ffffffff813f51b7)
Location: include/linux/mmap_lock.h:152
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
```
```
In fs/exec.c (ffffffff814b90e9)
Location: include/linux/mmap_lock.h:152
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff815650d1)
Location: include/linux/mmap_lock.h:152
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815700ed)
Location: include/linux/mmap_lock.h:152
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In arch/x86/kernel/shstk.c (ffffffff810ca3f5)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
```
```
In kernel/bpf/task_iter.c (ffffffff8134948a)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/oom_kill.c (ffffffff813c01fd)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/gup.c (ffffffff81410994)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
```
```
In mm/memory.c (ffffffff814157e6)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
```
```
In fs/exec.c (ffffffff814eb8d9)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff8159bd9a)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815a8a7d)
Location: include/linux/mmap_lock.h:150
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
