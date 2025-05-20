# Function: <code>__get_order</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts_rd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In init/initramfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/events/intel/cqm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034e44)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066e66)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f76557)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff81f7710a)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
```
In arch/x86/mm/init.c (ffffffff8181873c)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/pat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/mm/mpx.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/platform/efi/efi-bgrt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/pid.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/params.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/async.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/groups.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/sched/auto_group.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/livepatch/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/profile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/futex.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/module.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/acct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/cgroup_freezer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/cgroup_pids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/cpuset.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/relay.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/padata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/mempool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/page_alloc.c (ffffffff81194f3e)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/shmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/percpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ce5cf)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/nobootmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/memblock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/zswap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/sparse.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8181f0e4)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff811e77ab)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
```
```
In mm/memory_hotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fbebc)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/zbud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/cma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/frame_vector.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/read_write.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/exec.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/pipe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/select.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/dcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/splice.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/aio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/compat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/proc/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff812874f5)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/crypto_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ext4/crypto_fname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff812f2a75)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_alloc
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813064e6)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In ipc/util.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In ipc/sem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In ipc/shm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/ss/ebitmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/context.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/integrity/iint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813979f0)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_free_pages
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/aead.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/shash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/rng.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/bio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/blk-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/blk-tag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/genhd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/bsg.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/kobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/flex_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/percpu_ida.c (ffffffff813ff491)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/percpu_ida.c:__percpu_ida_init
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/swiotlb.c (ffffffff81412394)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/mpi/mpicoder.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In lib/digsig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/console/fbcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/console/bitblit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/console/softcursor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/console/fbcon_rotate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/console/fbcon_cw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/console/fbcon_ud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/console/fbcon_ccw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/sfi/sfi_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/pcpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d44be)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/agp/backend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/agp/isoch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/tpm/tpm_eventlog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/char/tpm/tpm_acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152f98d)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:__map_single
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f4bf1)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:tbl_size
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/dmar.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8153a3f2)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/lightnvm/sysblk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8155e006)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
```
In drivers/base/firmware_class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regcache-lzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/block/brd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8157549e)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
```
```
In drivers/misc/bmp085.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mfd/tps65912-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff815c4948)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/hsi/hsi_boardinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/phy/phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/dwc2/pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/power/power_supply_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/power/power_supply_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/md/bitmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/firmware/edd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/pci/i386.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In arch/x86/pci/bus_numa.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/sock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/dst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/neighbour.c (ffffffff8172494a)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81742b58)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/sched/sch_api.c:qdisc_class_hash_free
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8174d79e)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8179bf26)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/xfrm/xfrm_hash.c (ffffffff817bb55d)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8180544d)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts_rd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In init/initramfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/cqm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034126)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/htirq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81f9db50)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9f6f0)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff81f9f850)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
```
In arch/x86/mm/init.c (ffffffff81892283)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/pat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/platform/efi/efi-bgrt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sysctl_binary.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/pid.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/params.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/async.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/groups.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/auto_group.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/livepatch/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/profile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/futex.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/module.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/modsign_uefi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/acct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup_freezer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup_pids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cpuset.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/relay.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/padata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/mempool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/page_alloc.c (ffffffff81fb1280)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/shmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/percpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/vmalloc.c (ffffffff811eb367)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/nobootmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memblock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zswap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/sparse.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff818995e0)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/ksm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/slub.c (ffffffff81207763)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:slab_out_of_memory
```
```
In mm/memory_hotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memcontrol.c (ffffffff8121fef3)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zpool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zbud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/cma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/frame_vector.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/read_write.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/exec.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pipe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/select.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/dcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/libfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/splice.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/sync.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/aio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/keyinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/compat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/coredump.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/vmcore.c (ffffffff812b47d5)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/jbd2/journal.c (ffffffff813204c6)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_free
  - fs/jbd2/journal.c:jbd2_alloc
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/crypto.c (ffffffff8133a8a6)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/util.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/sem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/shm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/ebitmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/context.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/iint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813d3deb)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/aead.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/seqiv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/shash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/lzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/rng.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-tag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-mq-tag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/genhd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/badblocks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bsg.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/cfq-iosched.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/idr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/flex_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/percpu_ida.c (ffffffff81446c1d)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_destroy
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/once.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/swiotlb.c (ffffffff8145a0d4)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpicoder.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/digsig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/aer/aerdrv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/bitblit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/softcursor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_rotate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_cw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_ud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_ccw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/nvs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/glue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/dock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_apd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/property.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpeutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evglock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evxfgpe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nseval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ac.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_slot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/container.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ioapic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/apei-base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/sfi/sfi_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/system.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/pcpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815260a6)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/mcelog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/isoch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm_eventlog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm_acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff81584d28)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd612c)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:tbl_size
```
```
In drivers/iommu/dmar.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158ef00)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/lightnvm/sysblk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/dma-mapping.c (ffffffff815b2246)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
```
In drivers/base/isa.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/firmware_class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-lzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/brd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/virtio_blk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/xen-blkfront.c (ffffffff815c90ca)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dax_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/fence.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/fence-array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sg.c (ffffffff8161d150)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/virtio_net.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/phy/phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/serio/i8042.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/power/power_supply_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/power/power_supply_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/bitmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/debugfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/edd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/i386.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/mmconfig-shared.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/bus_numa.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/socket.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/scm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/neighbour.c (ffffffff8178e3fa)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/filter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_api.c (ffffffff817afa64)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_free
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/fib_semantics.c (ffffffff81809aa9)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_hash.c (ffffffff818284cd)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/packet/af_packet.c (ffffffff81875fd0)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/cqm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/xen/smp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/e820.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033d66)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_schemata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/htirq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81fd90dc)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fdac52)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff81fdadb2)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
```
In arch/x86/mm/init.c (ffffffff818c6ba3)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/pat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sysctl_binary.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/pid.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/params.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/async.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/groups.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/auto_group.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/livepatch/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/profile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/futex.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/module.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/modsign_uefi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/acct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup_freezer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup_pids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cpuset.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/relay.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/padata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/mempool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/page_alloc.c (ffffffff81fedb4e)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/shmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/percpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/vmalloc.c (ffffffff811fc5d7)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/nobootmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memblock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zswap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/sparse.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff818cdc98)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/ksm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/slub.c (ffffffff8121979b)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:slab_out_of_memory
```
```
In mm/memory_hotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memcontrol.c (ffffffff812325e5)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zpool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zbud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/cma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/frame_vector.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/read_write.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/exec.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pipe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/select.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/dcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/libfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/splice.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/sync.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/aio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/keyinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/compat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/coredump.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/iomap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/vmcore.c (ffffffff812ca065)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/jbd2/journal.c (ffffffff81336376)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_free
  - fs/jbd2/journal.c:jbd2_alloc
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/crypto.c (ffffffff81350646)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/util.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/sem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/shm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/ebitmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/context.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/iint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_fs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813eb82b)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/aead.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/skcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/seqiv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/shash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/acompress.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/scompress.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cbc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/xts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/lzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/rng.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-tag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/genhd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/badblocks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bsg.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/cfq-iosched.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/idr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/flex_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/iov_iter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/percpu_ida.c (ffffffff81465409)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_destroy
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/once.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/swiotlb.c (ffffffff81478ab4)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpicoder.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/digsig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/aer/aerdrv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/bitblit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/softcursor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_rotate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_cw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_ud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_ccw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/nvs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/glue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/dock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_apd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/property.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpeutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evglock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evxfgpe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nseval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsparse.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ac.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_slot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/container.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ioapic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/apei-base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/sfi/sfi_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/system.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/pcpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815525b6)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/mcelog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/isoch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm_eventlog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm_acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b1e01)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff820142ac)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:tbl_size
```
```
In drivers/iommu/dmar.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bca25)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff815be966)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/lightnvm/sysblk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/dma-mapping.c (ffffffff815e1536)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
```
In drivers/base/isa.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/firmware_class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-lzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/xen-blkfront.c (ffffffff815f5e1a)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dax_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sg.c (ffffffff8164dd50)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/phy/phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/serio/i8042.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/bitmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/debugfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/edd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/memmap.c (ffffffff820224f4)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/i386.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/mmconfig-shared.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/bus_numa.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/socket.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/scm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/neighbour.c (ffffffff817bbcca)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/filter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_api.c (ffffffff817df154)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_free
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/icmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/fib_semantics.c (ffffffff8183ac29)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_hash.c (ffffffff81859ead)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/packet/af_packet.c (ffffffff818aa4d4)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/dma-noop.c (ffffffff818c5521)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/dma-noop.c:dma_noop_free
  - lib/dma-noop.c:dma_noop_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/e820.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81031e26)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/apic/htirq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff820b9f41)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bbad4)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff820bbc44)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
```
In arch/x86/mm/init.c (ffffffff818fe300)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/pat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sysctl_binary.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/pid.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/params.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/async.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/groups.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/livepatch/patch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/profile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/futex.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/module.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/acct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/relay.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/padata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In certs/system_keyring.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In certs/blacklist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In certs/load_uefi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/mempool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/page_alloc.c (ffffffff820cf78c)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/shmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/percpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/vmalloc.c (ffffffff812072ab)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/nobootmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memblock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zswap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/sparse.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff8190514c)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/ksm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/slub.c (ffffffff812251eb)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:slab_out_of_memory
```
```
In mm/memory_hotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memcontrol.c (ffffffff8123d647)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zpool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zbud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In mm/cma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/read_write.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/exec.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pipe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/select.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/dcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/libfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/splice.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/sync.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/aio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/crypto/keyinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/coredump.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/iomap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/proc/vmcore.c (ffffffff812d7525)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/configfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/jbd2/journal.c (ffffffff8134b0a6)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_free
  - fs/jbd2/journal.c:jbd2_alloc
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/crypto.c (ffffffff81365156)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/util.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/sem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/shm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/commoncap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/security.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ibpkey.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/iint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/digsig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813f7b4b)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/aead.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/skcipher.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/seqiv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/shash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/acompress.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/scompress.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cbc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/cts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/xts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/rng.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-tag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-stat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/genhd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/badblocks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bsg.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/cfq-iosched.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/parser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/flex_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/percpu_ida.c (ffffffff8146a469)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_destroy
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/once.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/swiotlb.c (ffffffff81481ac5)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpicoder.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/digsig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/access.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/aer/aerdrv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff814d2d86)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/bitblit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/softcursor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_rotate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_cw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_ud.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/console/fbcon_ccw.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/ipmi/ipmi_dmi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/nvs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/glue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/dock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_apd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/property.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evgpeutil.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evglock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/evxfgpe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nseval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsparse.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ac.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/pci_slot.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/container.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/ioapic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/apei-base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/sfi/sfi_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/system.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/pcpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566d86)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/mcelog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/isoch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm1_eventlog.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/char/tpm/tpm_acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c7a91)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff820f5857)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:tbl_size
```
```
In drivers/iommu/dmar.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d2895)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff815d4586)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/dma-mapping.c (ffffffff815f61b6)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
```
In drivers/base/isa.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/firmware_class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/block/xen-blkfront.c (ffffffff8160a15a)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvdimm/dax_devs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/scsi/sg.c (ffffffff81662673)
Location: include/asm-generic/getorder.h:13
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/phy/phy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/serio/i8042.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-core-acpi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/bitmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mmc/core/debugfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/edd.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/memmap.c (ffffffff82105228)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/platform/x86/pmc_atom.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/i386.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/mmconfig-shared.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/pci/bus_numa.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/socket.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/scm.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/dst.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/neighbour.c (ffffffff817da3ca)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/filter.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_api.c (ffffffff817fe714)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_free
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/fib_semantics.c (ffffffff8185c964)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/xfrm/xfrm_hash.c (ffffffff8187dc5d)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/packet/af_packet.c (ffffffff818d1003)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/dma-virt.c (ffffffff818ebe81)
Location: include/asm-generic/getorder.h:13
Inline: True
Inline callers:
  - lib/dma-virt.c:dma_virt_free
  - lib/dma-virt.c:dma_virt_alloc
```
```
In lib/kobject.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/asm-generic/getorder.h:13
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/ds.c (ffffffff8100dea8)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/e820.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034156)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/crash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826c08f0)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c24b6)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff826c2626)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
```
In arch/x86/mm/init.c (ffffffff81988430)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/pat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810802fd)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_free
  - arch/x86/mm/mem_encrypt.c:sev_alloc
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/resource.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sysctl_binary.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/umh.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/params.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/async.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/groups.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/livepatch/patch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/livepatch/shadow.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/profile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/futex.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/module.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/acct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/utsname.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/pid_namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/relay.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/sockmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/padata.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/system_keyring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/blacklist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/load_uefi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/mempool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/page_alloc.c (ffffffff826d81ae)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/shmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/percpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/gup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/vmalloc.c (ffffffff8122039b)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/nobootmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memblock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zswap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/sparse.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff8198f131)
Location: include/asm-generic/getorder.h:14
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/ksm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/slub.c (ffffffff8124086b)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:slab_out_of_memory
```
```
In mm/memory_hotplug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memcontrol.c (ffffffff8125d213)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zpool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zbud.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/cma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hmm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/read_write.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/exec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pipe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/namei.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/select.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/dcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/libfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/splice.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/sync.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/aio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/keyinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/coredump.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/iomap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/proc_net.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/vmcore.c (ffffffff812fbc05)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/jbd2/journal.c (ffffffff8136f6f6)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_free
  - fs/jbd2/journal.c:jbd2_alloc
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/crypto.c (ffffffff81389e26)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/util.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/sem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/shm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/commoncap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/security.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ibpkey.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/digsig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8141fc4b)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/aead.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/skcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/seqiv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/shash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/acompress.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/scompress.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cbc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/xts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/gcm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/rng.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-tag.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-stat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/genhd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/badblocks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bsg.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/cfq-iosched.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-zoned.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/flex_array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/percpu_ida.c (ffffffff81496762)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_destroy
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/once.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/swiotlb.c (ffffffff814bd91f)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/nlattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpicoder.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/digsig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/access.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/aer/aerdrv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/softcursor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/ipmi/ipmi_dmi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/nvs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/glue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/dock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_apd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/property.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dspkginit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpeutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evglock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evxfgpe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nseval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsparse.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbcmds.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbconvert.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbexec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbhistry.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ac.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_slot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/container.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ioapic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/apei-base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/sfi/sfi_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/system.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-divider.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/time.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/pcpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815caf36)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/mcelog.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/isoch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm1_eventlog.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm_acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162e761)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff826fef17)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:tbl_size
```
```
In drivers/iommu/dmar.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/intel-iommu.c (ffffffff81639595)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff8163b316)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/dma-mapping.c (ffffffff8165e0d6)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
```
In drivers/base/isa.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/firmware_class.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/block/xen-blkfront.c (ffffffff81672a2a)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dax_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sg.c (ffffffff816cbcc3)
Location: include/asm-generic/getorder.h:14
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/phy/phy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/serio/i8042.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/edd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/memmap.c (ffffffff8270e8f1)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/platform/x86/pmc_atom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/i386.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/mmconfig-shared.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/fixup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/bus_numa.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/socket.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/scm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dst.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/neighbour.c (ffffffff81854b6a)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/filter.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc854)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xfrm/xfrm_hash.c (ffffffff818fea2d)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/packet/af_packet.c (ffffffff81955f03)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/dma-virt.c (ffffffff81971e71)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - lib/dma-virt.c:dma_virt_free
  - lib/dma-virt.c:dma_virt_alloc
```
```
In lib/kobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e665)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/enlighten.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/e820.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826eab2f)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826eba41)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff826ec843)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
```
In arch/x86/mm/init.c (ffffffff819e4ec7)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/pat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/mpx.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/resource.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/umh.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/params.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/async.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/groups.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/livepatch/patch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/livepatch/shadow.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/dma/mapping.c (ffffffff8110cb85)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_contiguous_remap
```
```
In kernel/dma/direct.c (ffffffff8110cf65)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/virt.c (ffffffff8110d1c5)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/virt.c:dma_virt_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff8110d8a1)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/futex.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/module.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/acct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/relay.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/xskmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/sockmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/padata.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/system_keyring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/blacklist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/load_uefi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/mempool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/page_alloc.c (ffffffff827026dc)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/shmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/percpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/gup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/vmalloc.c (ffffffff8124217b)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/nobootmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memblock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zswap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/sparse.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff819eb9ad)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/ksm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/slub.c (ffffffff81263be5)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:slab_out_of_memory
```
```
In mm/memory_hotplug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memcontrol.c (ffffffff81281c34)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zpool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zbud.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/cma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hmm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/read_write.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/exec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pipe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/namei.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/select.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/dcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/libfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/splice.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/sync.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/aio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/keyinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/coredump.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/iomap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/vmcore.c (ffffffff8270ee07)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/item.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/jbd2/journal.c (ffffffff8139dbc0)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_alloc
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/crypto.c (ffffffff813b8c96)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/util.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/sem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/shm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/request_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/commoncap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ibpkey.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/digsig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8145222a)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/aead.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/skcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/seqiv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/shash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/acompress.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cbc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/xts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/gcm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/deflate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/rng.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-tag.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-stat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/genhd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/badblocks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bsg.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/cfq-iosched.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/flex_array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/percpu_ida.c (ffffffff814cbb03)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/percpu_ida.c:percpu_ida_destroy
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/once.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/error-inject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/nlattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpicoder.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/digsig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/softcursor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/ipmi/ipmi_dmi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/nvs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/glue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/dock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_apd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/property.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dspkginit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpeutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evglock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evxfgpe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nseval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsparse.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbcmds.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbconvert.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbexec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbhistry.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ac.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_slot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/container.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ioapic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/apei-base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/sfi/sfi_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/system.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-divider.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/time.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/pcpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81603795)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/mcelog.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/isoch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/eventlog/tpm1.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff81669441)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff827291fb)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:tbl_size
```
```
In drivers/iommu/dmar.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/intel-iommu.c (ffffffff816747f1)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff81676835)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/isa.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/firmware_loader/fallback.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/block/xen-blkfront.c (ffffffff816ae515)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dax_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sg.c (ffffffff817085ed)
Location: include/asm-generic/getorder.h:14
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/serio/i8042.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pps/kapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/edd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/memmap.c (ffffffff82738bb0)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/platform/x86/pmc_atom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/i386.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/mmconfig-shared.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/fixup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/bus_numa.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/socket.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/scm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dst.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/neighbour.c (ffffffff818a019a)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/filter.c (ffffffff818b39e8)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/fib_semantics.c (ffffffff81933046)
Location: include/asm-generic/getorder.h:14
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xfrm/xfrm_hash.c (ffffffff8195550b)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/seg6_local.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/packet/af_packet.c (ffffffff819b1149)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xdp/xsk_queue.c (ffffffff819cd397)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/radix-tree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/amd/iommu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/ds.c (ffffffff8100eb35)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/e820.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a0702)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a17d8)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a2643)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff828a3434)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
```
In arch/x86/mm/init.c (ffffffff81a2008f)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/pat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/kmmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/resource.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/umh.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/params.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/async.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/groups.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/autogroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/irq/matrix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/livepatch/patch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/livepatch/shadow.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/dma/direct.c (ffffffff81118cf5)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff81118e95)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/virt.c:dma_virt_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff81119439)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/futex.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/module.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/acct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/freezer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/pids.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/user_namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/relay.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/tracing_map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/fgraph.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_events_hist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/btf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/xskmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/offload.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/bpf/cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/padata.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/system_keyring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/blacklist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In certs/load_uefi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/mempool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/page_alloc.c (ffffffff828b9e05)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/shmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/percpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/gup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/vmalloc.c (ffffffff812568ab)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memblock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zswap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/sparse.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/sparse-vmemmap.c (ffffffff81a26c30)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/ksm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/slub.c (ffffffff81278375)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:slab_out_of_memory
```
```
In mm/memory_hotplug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memcontrol.c (ffffffff81298bcf)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zpool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zbud.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/cma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/hmm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In mm/memfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/read_write.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/exec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pipe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/namei.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/select.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/dcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/libfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/splice.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/sync.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/aio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/hooks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/crypto/keyinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/coredump.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/iomap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/proc/vmcore.c (ffffffff828c5f76)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/configfs/symlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/fsmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/mballoc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/jbd2/journal.c (ffffffff813b6930)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_alloc
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/crypto.c (ffffffff813d2206)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/dir.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/util.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/sem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/shm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/commoncap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/security.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ibpkey.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/digsig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/platform_certs/load_uefi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8146f34a)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/aead.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/skcipher.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/seqiv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/shash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/acompress.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cbc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/cts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/xts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/gcm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/deflate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/rng.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-mq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-stat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/genhd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/badblocks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bsg.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/blk-zoned.c (ffffffff814cbbd6)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In block/sed-opal.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/flex_array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/once.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/error-inject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/nlattr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpicoder.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/digsig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/vpd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/proc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/softcursor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/ipmi/ipmi_dmi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/nvs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/sleep.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/glue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_pdc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/dock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_apd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/property.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dspkginit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpeblk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evgpeutil.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evglock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/evxfgpe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nseval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsparse.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbcmds.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbconvert.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbexec.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbhistry.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbnames.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpica/dbxface.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ac.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/button.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/pci_slot.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/container.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/thermal.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/ioapic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/battery.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/apei-base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/sfi/sfi_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/system.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-divider.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/time.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/pcpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161e885)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/mcelog.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/tty/serdev/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/hpet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/backend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/isoch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/agp/compat_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/eventlog/tpm1.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/iova.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687ca1)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e1449)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:tbl_size
```
```
In drivers/iommu/dmar.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/intel-iommu.c (ffffffff81692e21)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-pasid.c (ffffffff816940f1)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/swnode.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/isa.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/firmware_loader/fallback.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/block/xen-blkfront.c (ffffffff816cf455)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvdimm/dax_devs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/scsi/sg.c (ffffffff8172ab13)
Location: include/asm-generic/getorder.h:14
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/gpu/vga/vga_switcheroo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/spi/spi-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/quirks.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/serio/i8042.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/rtc/nvmem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-core-acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/media/cec/cec-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/media/cec/cec-notifier.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/pps/kapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_mc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_device.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_pci.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/eisa/eisa-bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/opp/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/opp/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/edd.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/memmap.c (ffffffff828f2b5c)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/platform/x86/pmc_atom.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In drivers/nvmem/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/i386.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/mmconfig-shared.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/xen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/fixup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/acpi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/common.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/pci/bus_numa.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/power/cpu.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In arch/x86/power/hibernate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/socket.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/scm.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/dst.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/neighbour.c (ffffffff818c2a5a)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/filter.c (ffffffff818d95a2)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/skmsg.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/core/sock_map.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_generic.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/bpf/test_run.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/fib_semantics.c (ffffffff819628d6)
Location: include/asm-generic/getorder.h:14
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/metrics.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xfrm/xfrm_hash.c (ffffffff8198a11b)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/icmp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/packet/af_packet.c (ffffffff819e852e)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In net/xdp/xsk_queue.c (ffffffff81a066c7)
Location: include/asm-generic/getorder.h:14
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/idr.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kobject.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
```
In lib/memcat_p.c (0)
Location: include/asm-generic/getorder.h:14
Inline: False
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
