# Function: <code>__is_vma_write_locked</code>

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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091b66)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097dac)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_mmap
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810d2fa5)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn_clear
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
```
```
In kernel/fork.c (ffffffff810f2779)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/relay.c (ffffffff81262efb)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_mmap
```
```
In kernel/bpf/syscall.c (ffffffff812ed662)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap
```
```
In kernel/bpf/ringbuf.c (ffffffff813339cd)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_user
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_kern
```
```
In kernel/events/core.c (ffffffff81374a61)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/shmem.c (ffffffff813bced4)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_mmap
```
```
In mm/memory.c (ffffffff813f39a2)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
```
```
In mm/mlock.c (ffffffff813f71b2)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff814014a7)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
```
```
In mm/mprotect.c (ffffffff81403ea1)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff81405cd5)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
```
In mm/pagewalk.c (ffffffff81408ef3)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_vma
  - mm/pagewalk.c:walk_page_range_vma
  - mm/pagewalk.c:walk_page_range
```
```
In mm/vmalloc.c (ffffffff814182de)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
```
```
In mm/madvise.c (ffffffff814286d9)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In mm/mempolicy.c (ffffffff8144cf5e)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/ksm.c (ffffffff814527c7)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/ksm.c:ksm_del_vmas
```
```
In mm/khugepaged.c (ffffffff8147d63e)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8149fca4)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_mmap
```
```
In fs/exec.c (ffffffff814b8ef1)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/userfaultfd.c (ffffffff815239e5)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_set_vm_flags
```
```
In fs/aio.c (ffffffff81527ac5)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/aio.c:aio_ring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81564db4)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/vmcore.c (ffffffff8157e42d)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/ext4/file.c (ffffffff815a2716)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e2d2)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/dax.c (ffffffff8166b1a1)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In security/selinux/selinuxfs.c (ffffffff816b5bd6)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy
  - security/selinux/selinuxfs.c:sel_mmap_policy
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819823c2)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
```
```
In drivers/scsi/sg.c (ffffffff81bf1773)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_mmap
```
```
In drivers/usb/core/devio.c (ffffffff81c99430)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In net/ipv4/tcp.c (ffffffff81f0a6ff)
Location: include/linux/mm.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_mmap
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098f16)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f31c)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_mmap
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810db735)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn_clear
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
```
```
In kernel/fork.c (ffffffff810fb25a)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/relay.c (ffffffff8127d11b)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_mmap
```
```
In kernel/bpf/syscall.c (ffffffff8130c212)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap
```
```
In kernel/bpf/ringbuf.c (ffffffff813580bd)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_user
  - kernel/bpf/ringbuf.c:ringbuf_map_mmap_kern
```
```
In kernel/events/core.c (ffffffff8139dd91)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/shmem.c (ffffffff813e7d24)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_mmap
```
```
In mm/memory.c (ffffffff8141e294)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
```
```
In mm/mlock.c (ffffffff81422703)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff8142dae6)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_shrink
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_link
```
```
In mm/mprotect.c (ffffffff814303b4)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/mremap.c (ffffffff814323d2)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
```
```
In mm/pagewalk.c (ffffffff81435613)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_page_vma
  - mm/pagewalk.c:walk_page_range_vma
  - mm/pagewalk.c:walk_page_range
```
```
In mm/vmalloc.c (ffffffff81444e2e)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
```
```
In mm/madvise.c (ffffffff81461f5f)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In mm/mempolicy.c (ffffffff81486851)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/ksm.c (ffffffff8148cdc6)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/ksm.c:ksm_del_vmas
```
```
In mm/khugepaged.c (ffffffff814af336)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814cf3f4)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_mmap
```
```
In fs/exec.c (ffffffff814eb6eb)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/userfaultfd.c (ffffffff81559bdc)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8155c855)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/aio.c:aio_ring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff8159b873)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/vmcore.c (ffffffff815b6e6d)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/ext4/file.c (ffffffff815db226)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In fs/hugetlbfs/inode.c (ffffffff81667782)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fuse/dax.c (ffffffff816a54e1)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_mmap
```
```
In security/selinux/selinuxfs.c (ffffffff816f2766)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy
  - security/selinux/selinuxfs.c:sel_mmap_policy
  - security/selinux/selinuxfs.c:sel_mmap_handle_status
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9b49)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap
```
```
In drivers/scsi/sg.c (ffffffff81c47033)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_mmap
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d094)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbe4b6)
Location: include/linux/mm.h:692
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81d4e19f)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In net/ipv4/tcp.c (ffffffff81fce77f)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_mmap
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
