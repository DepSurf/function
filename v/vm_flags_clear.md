# Function: <code>vm_flags_clear</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810d2fa5)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn_clear
  - arch/x86/mm/pat/memtype.c:untrack_pfn
```
```
In kernel/fork.c (ffffffff810f283f)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/bpf/syscall.c (ffffffff812ed662)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap
```
```
In kernel/bpf/ringbuf.c (ffffffff813339cd)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_user
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_kern
```
```
In mm/shmem.c (ffffffff813bced4)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
```
```
In mm/mmap.c (ffffffff814003e1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mremap.c (ffffffff81406090)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
```
In mm/ksm.c (ffffffff814527c7)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/ksm.c:ksm_del_vmas
```
```
In fs/exec.c (ffffffff814b8ef1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/proc/task_mmu.c (ffffffff81564db4)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e427)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In security/selinux/selinuxfs.c (ffffffff816b5bd6)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
```
```
In net/ipv4/tcp.c (ffffffff81f0a6ff)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_mmap
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
In arch/x86/mm/pat/memtype.c (ffffffff810db735)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn_clear
  - arch/x86/mm/pat/memtype.c:untrack_pfn
```
```
In kernel/fork.c (ffffffff810fb503)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/bpf/syscall.c (ffffffff8130c212)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap
```
```
In kernel/bpf/ringbuf.c (ffffffff813580bd)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_user
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_kern
```
```
In mm/shmem.c (ffffffff813e7d24)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
```
```
In mm/mmap.c (ffffffff8142c828)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mremap.c (ffffffff81432793)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
```
In mm/ksm.c (ffffffff8148cdc6)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - mm/ksm.c:ksm_del_vmas
```
```
In fs/exec.c (ffffffff814eb6eb)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/proc/task_mmu.c (ffffffff8159b873)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/hugetlbfs/inode.c (ffffffff816678ed)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In security/selinux/selinuxfs.c (ffffffff816f2766)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
```
```
In net/ipv4/tcp.c (ffffffff81fce77f)
Location: include/linux/mm.h:845
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_mmap
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
