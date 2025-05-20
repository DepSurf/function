# Function: <code>fatal_signal_pending</code>

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
In arch/x86/entry/common.c (ffffffff81003598)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
```
```
In arch/x86/mm/fault.c (ffffffff8106b25b)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/signal.c (ffffffff8108d9b2)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff8113bf78)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_phase2
```
```
In kernel/events/uprobes.c (ffffffff8118852e)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8118d4a6)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
```
```
In mm/oom_kill.c (ffffffff8119106b)
Location: include/linux/sched.h:2910
Inline: True
```
```
In mm/page_alloc.c (ffffffff81197896)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff81199852)
Location: include/linux/sched.h:2910
Inline: True
```
```
In mm/vmscan.c (ffffffff811a0e3b)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff811b569b)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_zone
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/gup.c (ffffffff811bab76)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff811df432)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff811fba09)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81207b5e)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/exec.c (ffffffff81212db1)
Location: include/linux/sched.h:2910
Inline: True
```
```
In fs/ioctl.c (ffffffff8121fbb6)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812457af)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/userfaultfd.c (ffffffff8125ae3e)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/ext4/mballoc.c (ffffffff812d5953)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81304a63)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff81345392)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8139c3a1)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/ablkcipher.c (ffffffff813a07ba)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - crypto/ablkcipher.c:crypto_alloc_ablkcipher
```
```
In drivers/pci/access.c (ffffffff8142e897)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_pci22_wait
```
```
In drivers/md/dm.c (ffffffff816a038f)
Location: include/linux/sched.h:2910
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
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
In arch/x86/entry/common.c (ffffffff8100347b)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/mm/fault.c (ffffffff8106b5d3)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/signal.c (ffffffff81090a32)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff81143d3b)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/events/uprobes.c (ffffffff8119abcd)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811a0085)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
```
```
In mm/page_alloc.c (ffffffff811ac7df)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811ae1ba)
Location: include/linux/sched.h:3187
Inline: True
```
```
In mm/vmscan.c (ffffffff811b840b)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff811d21ee)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811d53e4)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff811fda6d)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8121fa92)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8122d8fe)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff8123209f)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff81239bdf)
Location: include/linux/sched.h:3187
Inline: True
```
```
In fs/ioctl.c (ffffffff81247421)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8126e544)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/userfaultfd.c (ffffffff81283a0b)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/ext4/dir.c (ffffffff812be355)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812d2a2c)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/mballoc.c (ffffffff81305607)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81338ba8)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff8137ac32)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff813d92c6)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In drivers/pci/access.c (ffffffff81479e77)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/md/dm.c (ffffffff81701709)
Location: include/linux/sched.h:3187
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
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
In arch/x86/entry/common.c (ffffffff8100344e)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/mm/fault.c (ffffffff8106f211)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/signal.c (ffffffff810959b2)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff8114dc0b)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/events/uprobes.c (ffffffff811aa33e)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811af925)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/page_alloc.c (ffffffff811bcdb5)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811be879)
Location: include/linux/sched.h:3343
Inline: True
```
```
In mm/vmscan.c (ffffffff811c8a4b)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff811e20f6)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811e53f4)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8120e566)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812320ed)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8123fe39)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81244414)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff8124c921)
Location: include/linux/sched.h:3343
Inline: True
```
```
In fs/ioctl.c (ffffffff8125a407)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8128176a)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/userfaultfd.c (ffffffff8129752f)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8129ab34)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap.c (ffffffff812b0962)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff812d39a6)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812e876e)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/mballoc.c (ffffffff8131b5ce)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8134e948)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff81391082)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff813f0bd6)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In drivers/pci/access.c (ffffffff8149b303)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/md/dm.c (ffffffff81733469)
Location: include/linux/sched.h:3343
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
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
In arch/x86/entry/common.c (ffffffff810032f8)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/mm/fault.c (ffffffff8106e96e)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/signal.c (ffffffff810929b2)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff81150166)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/events/uprobes.c (ffffffff811b1906)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811b680a)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/page_alloc.c (ffffffff811c4fc9)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811c6760)
Location: include/linux/sched/signal.h:322
Inline: True
```
```
In mm/vmscan.c (ffffffff811d11d7)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff811ebec3)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811efb7c)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff812082a1)
Location: include/linux/sched/signal.h:322
Inline: True
```
```
In mm/hugetlb.c (ffffffff81219f2b)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8123d208)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8124bd32)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff8124fb9b)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812589ed)
Location: include/linux/sched/signal.h:322
Inline: True
```
```
In fs/ioctl.c (ffffffff81266db8)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8128ef7e)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff8129e48d)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff812a3a3f)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812a9753)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap.c (ffffffff812be5e9)
Location: include/linux/sched/signal.h:322
Inline: True
```
```
In fs/ext4/dir.c (ffffffff812e5350)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff812f209a)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813129b6)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff81317f33)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ecryptfs/read_write.c (ffffffff81363455)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff813a77d6)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff813fce70)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In drivers/pci/access.c (ffffffff814a54b3)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/md/dm.c (ffffffff8174c778)
Location: include/linux/sched/signal.h:322
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
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
In arch/x86/entry/common.c (ffffffff81003245)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/mm/fault.c (ffffffff81073a18)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/signal.c (ffffffff810998b2)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff8115cf26)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/events/uprobes.c (ffffffff811c54e6)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811cab45)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/page_alloc.c (ffffffff811d9d88)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811db572)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff811e66a7)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff81202230)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81206f21)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81234fe7)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8125ce06)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8126bf9a)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81271aec)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff8127ab79)
Location: include/linux/sched/signal.h:323
Inline: True
```
```
In fs/ioctl.c (ffffffff81289651)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812b1b7e)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff812c1973)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff812c683b)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812ccd40)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap.c (ffffffff812e1f89)
Location: include/linux/sched/signal.h:323
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81309d79)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8131661a)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81337181)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff8133c79c)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ecryptfs/read_write.c (ffffffff81388132)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff813ccfa6)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814253d2)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In drivers/pci/access.c (ffffffff814e42f1)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/md/dm.c (ffffffff817be947)
Location: include/linux/sched/signal.h:323
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
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
In arch/x86/entry/common.c (ffffffff8100393c)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/mm/fault.c (ffffffff81076374)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff8108b8fd)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In kernel/signal.c (ffffffff8109d882)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff8116b632)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8117a1a4)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff811e5a2a)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811ebbf8)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page_alloc.c (ffffffff811fa61a)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811fcfef)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81207c67)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff812235f0)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81227ca2)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81257f3b)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8128183c)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff81290bd8)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81297969)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812a16d5)
Location: include/linux/sched/signal.h:351
Inline: True
```
```
In fs/ioctl.c (ffffffff812afa3e)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812d9ab9)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff812ea735)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff812efd06)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812f6f53)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap.c (ffffffff8130ea36)
Location: include/linux/sched/signal.h:351
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81337d07)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813444a6)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81365800)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff8136ad1b)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ecryptfs/read_write.c (ffffffff813b6f2c)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff813fae05)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81458bf0)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In drivers/pci/vpd.c (ffffffff81525692)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/md/dm.c (ffffffff81806ec6)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/common.c (ffffffff81003a1e)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff8107c641)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81095386)
Location: include/linux/sched/signal.h:360
Inline: True
```
```
In kernel/signal.c (ffffffff810a5b42)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff81178cba)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81187174)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff811f6440)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811fc7a8)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page_alloc.c (ffffffff8120cd5e)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff8120fb0c)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8121a7e7)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff81236650)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8123b482)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8126c5f7)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8129881a)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff812a5bfa)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812ac775)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812b6425)
Location: include/linux/sched/signal.h:360
Inline: True
```
```
In fs/ioctl.c (ffffffff812c4bfe)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812eefa6)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff8130080c)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff81304a56)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8130c003)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap.c (ffffffff81325366)
Location: include/linux/sched/signal.h:360
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8134ef87)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8135c5f6)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8137dbc0)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff813831db)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff813c51b8)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff813d047c)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814173ec)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81475e10)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff814c3361)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In drivers/pci/vpd.c (ffffffff8153b512)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/md/dm.c (ffffffff81832ef6)
Location: include/linux/sched/signal.h:360
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810042c1)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff8107fba1)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff8109933a)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810aa812)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffff81185beb)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81194590)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff8120e1d2)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8121407d)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffff8121f02a)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8122a03b)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff81247b75)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124c999)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff8127317e)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/hugetlb.c (ffffffff812879a5)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812b3c96)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812c12bc)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c8ed5)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812d3185)
Location: include/linux/sched/signal.h:365
Inline: True
```
```
In fs/ioctl.c (ffffffff812e160e)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff813107cb)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff81321ae3)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff81326934)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff813335b1)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/iomap/buffered-io.c (ffffffff8134c02e)
Location: include/linux/sched/signal.h:365
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81377fc4)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8138574a)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813a4395)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813ac60d)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff813efa53)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb0ee)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff81444fc5)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814a3e3f)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff814f1a42)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In drivers/pci/vpd.c (ffffffff8156af1b)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/md/dm.c (ffffffff81876e5d)
Location: include/linux/sched/signal.h:365
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810042c1)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff81080c31)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff8109f934)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810b0e12)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (ffffffff8115914f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff81191b65)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811a0050)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff8121b812)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff812218ad)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffff8122caca)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81237ebb)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff81255fd5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125aec9)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff81281fee)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff81284dd5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812975b5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812c5593)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812d320c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812da8e5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812e4d15)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ioctl.c (ffffffff812f30de)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff813237ab)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff81334046)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff813396c4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81347171)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff8134f76b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff813642fe)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81390364)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8139e19a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813bd205)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813c553d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81409ac3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81414fbe)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff8145eb35)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814bea6f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff8150affe)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81513789)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8158beeb)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff816baeb0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (ffffffff818a8a2d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810052cf)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff81087be0)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a69ed)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810b8e42)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/kexec_core.c (ffffffff81169f8f)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a6a6c)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5680)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff8124802e)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8124e49d)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffff8125a558)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81266f10)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff812846bd)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_finished
  - mm/compaction.c:compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81289e64)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff812adf54)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff812b6fb3)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812cabaa)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812fb251)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81308ef3)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81310e34)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff8131d964)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
```
```
In fs/ioctl.c (ffffffff8132b813)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8135a773)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff8136e40f)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff81373925)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff81386032)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_flush
```
```
In fs/dax.c (ffffffff8138c960)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81395efa)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/iomap/buffered-io.c (ffffffff813abd39)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813db923)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813ea03b)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8140937b)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff81411942)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81457690)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8146327e)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814b5c21)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8151f22c)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff8156a433)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
```
In block/blk-iocost.c (ffffffff81574b36)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff81632dfb)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff8176f1bb)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8182a8f4)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81977bbd)
Location: include/linux/sched/signal.h:366
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/mm/fault.c (ffffffff8108830e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a2501)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810b40f2)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/entry/common.c (ffffffff8113b8c0)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/kexec_core.c (ffffffff811666cf)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a40e9)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2f5e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff8125273e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81258a8d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
```
```
In mm/page-writeback.c (ffffffff812646dc)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81271960)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
```
```
In mm/compaction.c (ffffffff8128e9e0)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81293b59)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff812b998e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff812c1ef3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812d67ca)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8130704d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81314c54)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81327abb)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/ioctl.c (ffffffff81336dd3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/remap_range.c (ffffffff81366305)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff81367746)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff8137b654)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff81381808)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/io_uring.c (ffffffff8139749b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_flush
```
```
In fs/dax.c (ffffffff8139e0f0)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813a7c1a)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/iomap/buffered-io.c (ffffffff813bd209)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813ed388)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813fc41b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8141b882)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff81424df2)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81473a50)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8147eace)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814d3901)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8153c0b3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff81584e95)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
```
In block/blk-iocost.c (ffffffff8159186a)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff81657f4b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff81789b9b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b2e0)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff8197c84d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/mm/fault.c (ffffffff81088e25)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a31f2)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810b4f52)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/entry/common.c (ffffffff8113cb95)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/kexec_core.c (ffffffff8116746f)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a4a07)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b37ee)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff812565ca)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8125cf8d)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/page-writeback.c (ffffffff812688eb)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81276c50)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
```
```
In mm/compaction.c (ffffffff81294070)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff812994f6)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff812c217b)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff812c8db2)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812dd97d)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8130d6e1)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8131b347)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8132d8ab)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/ioctl.c (ffffffff8133cf33)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/remap_range.c (ffffffff8136cd0c)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8136e186)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff81381dd4)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff81388a85)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff813a51b6)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813aec7c)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff813b058b)
Location: include/linux/sched/signal.h:380
Inline: True
```
```
In fs/coredump.c (ffffffff813bf06e)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff813c4359)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813f39ee)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff81402ca1)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81421a96)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff8142baf6)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff8147949c)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81484652)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814da381)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815447a3)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff8158db11)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff815986cb)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8163a76b)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff8176d40b)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e4ea)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818902ee)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/md/dm.c (ffffffff819606dd)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/mm/fault.c (ffffffff81098294)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810b4998)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810c7012)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:task_join_group_stop
```
```
In kernel/entry/common.c (ffffffff8115fcb5)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/kexec_core.c (ffffffff8118cfdf)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811ce1ff)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811dd5be)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff8129229c)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81298e9c)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/oom_kill.c (ffffffff812a3812)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812a537d)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff812b4580)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
```
```
In mm/compaction.c (ffffffff812d45ed)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff812d9e40)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff81305af9)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8130ddd3)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81324b3d)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff81358796)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81368237)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8137b0cb)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff813bb9cc)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff813bd255)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff813cf024)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff813d5daa)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/io-wq.c (ffffffff813f16ec)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
```
```
In fs/dax.c (ffffffff813f497b)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff813fe81c)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff8140017b)
Location: include/linux/sched/signal.h:378
Inline: True
```
```
In fs/coredump.c (ffffffff8140ee9e)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff81413988)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81445ab1)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff81455371)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814743ed)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8147f996)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff814d0adb)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbcd2)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff81533281)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815a4f43)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff815f3580)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff815ffeb5)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff816ab2ae)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/char/mem.c (ffffffff817f2d9b)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8975)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923ee1)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/md/dm.c (ffffffff81a0837d)
Location: include/linux/sched/signal.h:378
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int fatal_signal_pending(struct task_struct *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810aaeee)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810c979c)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810e4d1a)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/entry/common.c (ffffffff8118a1bd)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/kexec_core.c (ffffffff811bc22f)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff812024aa)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8121433c)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff812e7b73)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff812ef760)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
```
```
In mm/oom_kill.c (ffffffff812fb74e)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812fdec0)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8131055d)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff813335a2)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81339b6a)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff81360708)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_area_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81371d3c)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff81377162)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff813932d3)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff813d2732)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff813e5bc7)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff813fb62f)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff81441c2d)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff81443481)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff81457dd4)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff8145e2f3)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff81467fd5)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81472339)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81473f9e)
Location: include/linux/sched/signal.h:408
Inline: True
```
```
In fs/coredump.c (ffffffff814845ce)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8148b181)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff814c1af7)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff814d2bee)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814f62d2)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff815029e9)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff8155d665)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8156994c)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff815c5604)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8164bb8d)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff816a4b07)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff816b255a)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff816da7d6)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff817ce335)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f26c8)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79871)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/md/dm.c (ffffffff81b70718)
Location: include/linux/sched/signal.h:408
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff810c7f60-ffffffff810c7f8a: fatal_signal_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int fatal_signal_pending(struct task_struct *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c4be4)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810e6d91)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8110537a)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/entry/common.c (ffffffff811c66fd)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/kexec_core.c (ffffffff811fe45f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8124a08f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8125de4c)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81351860)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8135a4c0)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
```
```
In mm/oom_kill.c (ffffffff8136585e)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff81368884)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81383bcd)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff813aa2a7)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff813b35c8)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff813e2883)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813ef51c)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff813f4762)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81411a64)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff81457eb5)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8146d6c6)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff814856cf)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff814d0f0d)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff814d2a31)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff814e7124)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff814edf81)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff814f831b)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81503e31)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815061f0)
Location: include/linux/sched/signal.h:409
Inline: True
```
```
In fs/coredump.c (ffffffff81517aae)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8151f1b9)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81559dae)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8156b79e)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8159069f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8159d4e9)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff815ff6b5)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d585)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff816721f4)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81704d8d)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff81763897)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81771a9f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff817a68c6)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff818edde5)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b7059b)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81d0d75a)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff810e55e0-ffffffff810e560a: fatal_signal_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int fatal_signal_pending(struct task_struct *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c8174)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810f27b1)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81111609)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:unhandled_signal
```
```
In kernel/entry/common.c (ffffffff811d931d)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/kexec_core.c (ffffffff81213729)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8126137f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff812750bc)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81382ad9)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8138bdd4)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
```
```
In mm/oom_kill.c (ffffffff81397cfe)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff8139aa24)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813b567d)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff813dd542)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff813e2bae)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff81417440)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81423095)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff81427d2a)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81444ef4)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8148dbf7)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814a21a7)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814ba72f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff81507a3f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8150933e)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff8151d974)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff81524464)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff8152fae3)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff8153b8b7)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff8153d522)
Location: include/linux/sched/signal.h:409
Inline: True
```
```
In fs/coredump.c (ffffffff8154f39e)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff815572e4)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81591bdc)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815a364e)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815c7852)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff815d3d35)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81637695)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8164543f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff816aa739)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8173efad)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff817a2936)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817b0d6a)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff817e783c)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff819312c5)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3e8f)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81d766a5)
Location: include/linux/sched/signal.h:409
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff810f0c90-ffffffff810f0cba: fatal_signal_pending (STB_LOCAL)
ffffffff814a0750-ffffffff814a077a: fatal_signal_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int fatal_signal_pending(struct task_struct *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810d064d)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810fb473)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
Direct callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8111afa9)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:unhandled_signal
```
```
In kernel/entry/common.c (ffffffff811eec5d)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
```
```
In kernel/kexec_core.c (ffffffff8122b659)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8127b57f)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8128f9e3)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff813abea9)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff813b5944)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
```
```
In mm/oom_kill.c (ffffffff813c1b2e)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff813c495f)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813de66d)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff814074a2)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff8140d3ee)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff81443f50)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144ffc5)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff8146153b)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff814bd567)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814d342b)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814eccaf)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff8153c1c0)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8153e25e)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff81551f54)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff81558c92)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff815649c3)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81570b94)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff81572982)
Location: include/linux/sched/signal.h:401
Inline: True
```
```
In fs/coredump.c (ffffffff815851de)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8158d814)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff8159bd8f)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
```
```
In fs/ext4/dir.c (ffffffff815ca94c)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815dc48e)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815f963e)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_interrupted
```
```
In fs/ext4/namei.c (ffffffff8160c3a5)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81670b85)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e961)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff816e778c)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8177fe2d)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff817e647b)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817f4b7a)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff8182d64b)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff81979de5)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c186af)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81e2d8d5)
Location: include/linux/sched/signal.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff810fa080-ffffffff810fa0aa: fatal_signal_pending (STB_LOCAL)
ffffffff814cfdf0-ffffffff814cfe1a: fatal_signal_pending (STB_LOCAL)
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
In arch/arm64/kernel/ptrace.c (ffff80001008efc4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
```
```
In arch/arm64/kernel/sys_compat.c (ffff8000100a16a8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/arm64/kernel/sys_compat.c:compat_arm_syscall
```
```
In arch/arm64/mm/fault.c (ffff800010da9128)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
```
```
In kernel/fork.c (ffff8000100f3f88)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffff80001010c870)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (ffff8000101c8780)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffff80001020956c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffff800010217884)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffff8000102a6ff8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffff8000102ae2f8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffff8000102bb6ac)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffff8000102c8c2c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffff8000102ed578)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffff8000102f25e4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffff80001031a744)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffff80001031f14c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffff800010335400)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffff80001036841c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffff800010378d00)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffff80001037ff44)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffff80001038d7c8)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ioctl.c (ffff80001039de34)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffff8000103dcafc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffff8000103f27d0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffff8000103f781c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffff80001040746c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffff800010411170)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffff80001042b5f8)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (ffff800010462c70)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffff800010471768)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffff800010493f10)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffff80001049d0a0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffff8000104e9f68)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffff8000104f6600)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffff80001055411c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffff8000105b7ae0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffff80001060e984)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffff800010617cb0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffff8000106f0f8c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffff8000108ab350)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (ffff800010afcb98)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030d184)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
```
```
In arch/arm/kernel/traps.c (c030fb64)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:arm_syscall
```
```
In arch/arm/mm/fault.c (c0e9f998)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
```
In kernel/fork.c (c03529b8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (c0364bb4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (c040f6fc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (c0448350)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (c045729c)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In kernel/events/uprobes.c (c04d6178)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (c04db868)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (c04e7fe4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (c04f7054)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (c0511494)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_unlock_should_abort
  - mm/compaction.c:compact_unlock_should_abort
```
```
In mm/gup.c (c05147a0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (c0534d20)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (c0537a50)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (c0559860)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (c05641f4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c056abb8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (c0574a38)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
```
```
In fs/ioctl.c (c058313c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (c05b5f64)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (c05c66b4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/userfaultfd.c (c05cb53c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/verity/enable.c (c05dd7cc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (c05f40a4)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (c0622ec0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (c0632630)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (c0655548)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (c065eec0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (c06a7ef8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (c06b411c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (c07072e8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (c076669c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (c07b9198)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (c07c3014)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (c088b9c0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (c09a7690)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (c0bdec04)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/powerpc/kernel/ptrace.c (c0000000000195c8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
```
```
In arch/powerpc/mm/fault.c (c000000000086a10)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In kernel/fork.c (c00000000013a334)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (c0000000001537ac)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (c000000000230e20)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (c000000000286638)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (c00000000029b7d4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (c00000000035a300)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (c000000000363788)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (c000000000373f38)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (c000000000384df8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (c0000000003b12ec)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0000000003b8c54)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (c0000000003eda5c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (c0000000003f3b70)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (c00000000040f3ac)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (c000000000456140)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (c00000000046bca0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c000000000475f3c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (c000000000484450)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ioctl.c (c0000000004985ac)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (c0000000004e20a8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (c0000000004f83c0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (c0000000005009ec)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c000000000512d54)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (c00000000051ecc8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (c00000000053c6d0)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (c00000000057f618)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (c000000000592068)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (c0000000005bced4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (c0000000005c8310)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (c000000000627e18)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (c000000000637554)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (c0000000006a424c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (c00000000073c698)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (c0000000007abf4c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (c0000000007b73cc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (c00000000086e674)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (c000000000942d04)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (c000000000bed890)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b64ba)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
```
```
In arch/riscv/mm/fault.c (ffffffe0000b9c54)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In kernel/fork.c (ffffffe0000c0758)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffe0000cdf58)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/seccomp.c (ffffffe00016b610)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffe000177b6e)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In mm/filemap.c (ffffffe0001d4f0c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffe0001de91c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffe0001e8196)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffe000201ba0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffe000204c0e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffe00021fecc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffe000220bf4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffe000231ab4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffe000246156)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffe00025062e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffe000255832)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffe00025dc4e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
```
```
In fs/ioctl.c (ffffffe0002696d8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffe000294da0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffe0002a33b6)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/userfaultfd.c (ffffffe0002a82f4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffe0002b22c2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffe0002b959a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8ef2)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (ffffffe0002f1622)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffe0002fd936)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffe000318a4c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffe00031fec6)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffe00035aeec)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffe0003652dc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffe0003a9762)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffe0003fe09e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffe000446df0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffe00044e248)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffe0004c48e4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffe0005601bc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (ffffffe0006eef4e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810042c1)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff8107fc31)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81099254)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810ab182)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (ffffffff8115176f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8118a185)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81198670)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81213e62)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81219efd)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffff8122511a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8123050b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff8124e625)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81253519)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff8127a63e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8127d425)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8128fb95)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812bdb73)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812cb7ec)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d2ec5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812dd2f5)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ioctl.c (ffffffff812eb6be)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8131bd8b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff8132c626)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff81331ca4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133f751)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81347d4b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8135c8de)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81388944)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8139677a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813b57e5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813bdb1d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff814020a3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d59e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff81457115)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814b704f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff815035de)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff8150bd69)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8157fd6b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff81680910)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/nvme/host/core.c (ffffffff81742f81)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_wait_ready
  - drivers/nvme/host/core.c:nvme_wait_ready
```
```
In drivers/md/dm.c (ffffffff8184e8ad)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81002791)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff8106ec94)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81087ca4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff81099b22)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (ffffffff81144a4f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8117d2b5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8118bb80)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81206bd2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8120d10d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffff812182ba)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff812235cb)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff812415c5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81246232)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff8126c52e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8126f290)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81281855)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812aecab)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812bc660)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c3b45)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812cdf75)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ioctl.c (ffffffff812dc2ee)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8130c92b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff8131bf11)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff8132286e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81330411)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81338a2b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8134d57e)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813793d4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8138720a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813a6275)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813ae5ad)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff813f2b23)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe01e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff81447b55)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814a7a6f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff814f3a9e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff814fc1b3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8156eb4b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff8165e5e0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/nvme/host/core.c (ffffffff81724c11)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_wait_ready
  - drivers/nvme/host/core.c:nvme_wait_ready
```
```
In drivers/md/dm.c (ffffffff81815ecd)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004281)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff8107fbe1)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81099204)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810aa6e2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (ffffffff8114f61f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff81187f55)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81196440)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81211c02)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81217c9d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffff81222eba)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8122e2ab)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff8124c3c5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812512b9)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff812783de)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8127b1c5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8128d9a5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812bb983)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812c95fc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d0cd5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812db105)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ioctl.c (ffffffff812e94ce)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8131985b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff8132a0f6)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff8132f774)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133d221)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff8134581b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8135a3ae)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813862a4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813940da)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813b3045)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813bb4fd)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff813ff423)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a91e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814531b5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814b30df)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff814ff66e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81507df9)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8157fc3b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff816aecf0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (ffffffff8189dedd)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/netfilter/nfnetlink.c (ffffffff819989c3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810043be)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/mm/fault.c (ffffffff81081cde)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a0e3d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/signal.c (ffffffff810b27c2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kexec_core.c (ffffffff8115c43f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811958a9)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811a4050)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81220b50)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81226d59)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/page-writeback.c (ffffffff8123209d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8123d6ab)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff8125bd25)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81260c3c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff81287fce)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8128ad95)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8129d75e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812cc111)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812da24d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812e1b05)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812ec0ad)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ioctl.c (ffffffff812fa4bd)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8132b4ed)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (ffffffff8133abce)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff813410d4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81350931)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81358afb)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/iomap/buffered-io.c (ffffffff8136dafe)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81399f94)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813a816a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813c7b95)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813d00b1)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81415053)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff814205de)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff8146acb4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814cbb5f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-cgroup.c (ffffffff81518819)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff8151f0d5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8159a0eb)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/char/mem.c (ffffffff816c8e15)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (ffffffff818ba7cd)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
