# Function: <code>__atomic_add_unless</code>

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
In arch/x86/events/core.c (ffffffff81005c25)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In kernel/cred.c (ffffffff810a2575)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/fair.c (ffffffff810badf1)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810c9c8c)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810cfa42)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810d55d0)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/module.c (ffffffff81105910)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup.c (ffffffff81114d4a)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81133805)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff8117a061)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (ffffffff811857f1)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81187b95)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff8118aec6)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
```
```
In mm/filemap.c (ffffffff8118cfa4)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
```
```
In mm/swap.c (ffffffff8119d35b)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811a2683)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/rmap.c (ffffffff811cbc40)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/swapfile.c (ffffffff811d584b)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff811d7e03)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff811dfaaf)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff811e4aed)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff8181a62a)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
```
```
In mm/migrate.c (ffffffff811f147c)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff811f59ec)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff811faa3b)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812016bb)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/balloon_compaction.c (ffffffff812074fe)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_isolate
```
```
In mm/page_idle.c (ffffffff81208152)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff8120f106)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8125ac91)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812772bd)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8127a7bd)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_net.c (ffffffff81286405)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/kernfs/mount.c (ffffffff81288a03)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/ext4/balloc.c (ffffffff8128f04c)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81292e94)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/super.c (ffffffff812ba700)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mballoc.c (ffffffff812cd604)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In ipc/util.c (ffffffff81324c25)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/keyring.c (ffffffff813318e0)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813751aa)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
```
```
In security/apparmor/context.c (ffffffff81377378)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
```
```
In security/apparmor/domain.c (ffffffff8137a6ca)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff8137fc5a)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/procattr.c (ffffffff81382dc0)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81383adc)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/resource.c (ffffffff8138754e)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81388bb0)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81389267)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/net.c (ffffffff81390ab0)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81392aff)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
```
```
In lib/dec_and_lock.c (ffffffff813e9307)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
```
```
In lib/kobject.c (ffffffff813ebf83)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
```
In drivers/phy/phy-core.c (ffffffff8141bd33)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429f85)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
```
```
In drivers/pci/pci-driver.c (ffffffff8143a719)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b65f5)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fddd6)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff8151aa8b)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff8153bbdc)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff81555e1c)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_disable
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a346b)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815a505a)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b32e7)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff8160c35a)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81613c12)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8161fbd2)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81662403)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff816c9c3a)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816ca761)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff817007ec)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff817068e3)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/neighbour.c (ffffffff817245d0)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/fib_rules.c (ffffffff81739c3c)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff81754310)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inetpeer.c (ffffffff817585ac)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81760061)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762624)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8176388f)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cbd9)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f30b)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81789998)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817adf4e)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/ipv6/addrlabel.c (ffffffff817d2f56)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff817d5464)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff817e2464)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff817e5e61)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0645)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f676e)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81801ead)
Location: arch/x86/include/asm/atomic.h:209
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/klist.c (ffffffff81817464)
Location: arch/x86/include/asm/atomic.h:209
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
In arch/x86/events/core.c (ffffffff810059e2)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In kernel/cred.c (ffffffff810a5cb5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/fair.c (ffffffff810be09a)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810ce605)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810d45e4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810da40d)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810e4487)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff811077b8)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8110d1e2)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup.c (ffffffff8111b555)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113bc45)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff81190b3e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81197daf)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8119a245)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811a1749)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/oom_kill.c (ffffffff811a4a86)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task
```
```
In mm/swap.c (ffffffff811b3a5e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811b89bd)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/rmap.c (ffffffff811e8ed4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff811f3871)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff811f6b5e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff811fe14f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812035c0)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818940d6)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In mm/migrate.c (ffffffff8121186b)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81217fbb)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff8121db0d)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81225f96)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8122db83)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81235b36)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff81282bd0)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/posix_acl.c (ffffffff81299556)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812a386d)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812a7474)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_net.c (ffffffff812b35a5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/kernfs/mount.c (ffffffff812b5ec3)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/ext4/balloc.c (ffffffff812bd24e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c3159)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/super.c (ffffffff812ec037)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/mballoc.c (ffffffff81305551)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In ipc/util.c (ffffffff81359815)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/keyring.c (ffffffff81366687)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813accfb)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813b0593)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813b7d42)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813bad33)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813bd064)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813be382)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813c1fef)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c3715)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813c8b4f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff813ca285)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813cc047)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813ceaec)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In lib/dec_and_lock.c (ffffffff8142f510)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In lib/kobject.c (ffffffff81431b63)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
```
In drivers/phy/phy-core.c (ffffffff81464393)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81486639)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505fc5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154eb02)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8155306c)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/hw_random/core.c (ffffffff8156d7bb)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff8159071c)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff815a9d6f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa538)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc105)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b747)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff8166bf24)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816740f9)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81680567)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c2633)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81716f2b)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8172cc0a)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172d711)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff817671b8)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8176ecc7)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/neighbour.c (ffffffff8178dfa0)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/fib_rules.c (ffffffff817a5f96)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff817c3169)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff817c488f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cc2f4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce6f1)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfd5f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff817d7a6e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec142)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec80f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff817f8066)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181af2e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/ipv6/addrlabel.c (ffffffff81840956)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81843374)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff818507aa)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81854282)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860cc1)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8186514e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/calipso.c (ffffffff818702d6)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873572)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81890f24)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
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
In arch/x86/events/core.c (ffffffff81006282)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff8103821e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103dd85)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/cred.c (ffffffff810ab915)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff810b7039)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
```
```
In kernel/sched/fair.c (ffffffff810c3598)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810d5245)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810db193)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e0edd)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810ead27)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8110ef83)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81114c52)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup.c (ffffffff81123895)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811459f5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff811a36c6)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811a778f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811a99b5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811b15b9)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/oom_kill.c (ffffffff811b4c09)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/swap.c (ffffffff811c40ee)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811c8fed)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/rmap.c (ffffffff811fa3b4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812043a2)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81207512)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8120ec1f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812155ca)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818c87d3)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In mm/migrate.c (ffffffff81223a27)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a55b)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812300ed)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81238576)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812400c8)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81248746)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff812966f0)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/posix_acl.c (ffffffff812ae076)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812b925d)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812bcda4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_net.c (ffffffff812c8df5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/kernfs/mount.c (ffffffff812cb753)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/ext4/balloc.c (ffffffff812d289e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d8749)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/super.c (ffffffff81301ff7)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/mballoc.c (ffffffff8131b518)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In ipc/util.c (ffffffff8136fcf5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/keyring.c (ffffffff8137cea7)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813c3b08)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813c7713)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813cf15e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813d20fb)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813d4494)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d5802)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813d948f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813daca5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813e0167)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff813e1905)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813e36c7)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813e616c)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/bsg-lib.c (ffffffff81437d95)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/dec_and_lock.c (ffffffff8144b740)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In lib/kobject.c (ffffffff8144ddd3)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
```
In lib/syscall.c (ffffffff81479f70)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff81483693)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814a7df9)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152a1c5)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b382)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157fb61)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/hw_random/core.c (ffffffff81599f1f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff815bdfad)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff815c807d)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff815d85b8)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81628808)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ad12)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/scsi/hosts.c (ffffffff8162f5da)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163afe7)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff81699c24)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816a1d89)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816ae297)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f05f3)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748d0b)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8175ebd8)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817606d1)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff81794238)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8179b951)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/neighbour.c (ffffffff817bb950)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/fib_rules.c (ffffffff817d4a6f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff817f18f1)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff817f43af)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fbe5d)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe501)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ffb4f)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81807a0e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b435)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d0ff)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81828f06)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c7ee)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854319)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81859302)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrlabel.c (ffffffff818725d6)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff818750e4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff818825f9)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81885fa4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f502)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8189781e)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/calipso.c (ffffffff818a3246)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7be2)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff818c56b4)
Location: arch/x86/include/asm/atomic.h:237
Inline: True
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
In arch/x86/events/core.c (ffffffff81006032)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff81036397)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103be15)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In kernel/cred.c (ffffffff810a8515)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3369)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810bdd61)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810d4235)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810da2b6)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e0042)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810ea3ff)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8111015a)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81115bc4)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811477a5)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffffffff81192695)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811aad31)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811aef2f)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811b1040)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811b7854)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/oom_kill.c (ffffffff811bc5ce)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/swap.c (ffffffff811cc4e0)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811d1b27)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff811f0b92)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/rmap.c (ffffffff812050a4)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8120fb10)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81212c2b)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8121a4cf)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81220bea)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818ffdd2)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In mm/migrate.c (ffffffff8122f387)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812361b5)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8123b289)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812440b6)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8124bf88)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81254066)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/notify/mark.c (ffffffff81299295)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark_safe
```
```
In fs/userfaultfd.c (ffffffff812a3e97)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/posix_acl.c (ffffffff812bb5d6)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812c6319)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812cccb3)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff812d440b)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff812d654a)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
```
```
In fs/kernfs/mount.c (ffffffff812d8ba3)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/configfs/item.c (ffffffff812e1c2e)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff812e3f62)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812f6b63)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813130f1)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81336f37)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In ipc/util.c (ffffffff81383185)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8138f415)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81390c41)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813d9f7b)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813dcffa)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813e2f0e)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813e4933)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813e7347)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813e9c83)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813ea7bc)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813ebd9b)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813ef62a)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff813f06d6)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813f1bad)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813f3765)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/bsg-lib.c (ffffffff81445555)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff81483280)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8148d91b)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814b1da9)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c996)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158fa32)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8159389f)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/hw_random/core.c (ffffffff815adeff)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3659)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff815dcd16)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff815ecb88)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163e46a)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff81640418)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/scsi/hosts.c (ffffffff816446a5)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164f6c4)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff816af636)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816b7602)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c3cf1)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705f21)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726f9f)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817673cb)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e4d8)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f2cc)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff817b260a)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff817bd0a3)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/dev.c (ffffffff817c7e1c)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff817da1a0)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff817e9f17)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/fib_rules.c (ffffffff817f3d8a)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff817f95c2)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff81812ac7)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff818147e3)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff81817646)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181c1ef)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e8a9)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fd39)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81828459)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81832a7f)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183bf15)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d915)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818416e2)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8184a2e4)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/icmp.c (ffffffff8184dd9b)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8187023e)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff818777a0)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_get
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8187d295)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff8188764c)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff81889937)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/addrconf.c (ffffffff8188ee71)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81897362)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff8189db64)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff818a95ca)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff818ac6b5)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5a25)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bdc2e)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/fib6_rules.c (ffffffff818c71ef)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff818c9ace)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce47a)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff818ebe00)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In lib/klist.c (ffffffff818edb94)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
```
```
In lib/kobject.c (ffffffff818ee058)
Location: arch/x86/include/asm/atomic.h:239
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff810063b2)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff81038727)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e911)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/cred.c (ffffffff810aecb5)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3a5d)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810c5a51)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810dc19c)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810e2462)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e82ee)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810f290f)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8111df52)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81121154)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81154035)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffffffff811a045c)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/events/core.c (ffffffff811be64d)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811c2abf)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811c4c20)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811cbdd4)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff811e14d0)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811e6fc6)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81205711)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/rmap.c (ffffffff8121e054)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8122b3ef)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8123563f)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8123be75)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81989f1c)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124cf65)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81254ff8)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8125ab19)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81263f36)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8126c342)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81276176)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff812c731a)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/posix_acl.c (ffffffff812deeca)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812ea1f9)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812f1553)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff812f4924)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff812f8c3b)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff812fad9a)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
```
```
In fs/kernfs/mount.c (ffffffff812fd403)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff812ff2b1)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/ext4/balloc.c (ffffffff81308958)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8131b193)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813378b1)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8135b4c2)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In lib/syscall.c (ffffffff814bf2c0)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff814c9a7b)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814f148e)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f4a6)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f4532)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f870f)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a354)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff81643d16)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81653f38)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff816ad638)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/net/loopback.c (ffffffff816f7432)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8171ac92)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81722ec2)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172fad1)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817770f1)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817985ef)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798908)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd2fd)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4a7a)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f5881)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811984)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff8182a7ca)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81831c30)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff8183d1f8)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/core/dev.c (ffffffff8184a0ba)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81855da9)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818655a7)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81876ed5)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff8188d8d5)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81892107)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81896884)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81897a2f)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189b145)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b999a)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd02b)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0efa)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff818c67de)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cb698)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cda86)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818e9eb5)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8fba)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff449)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffa96)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/anycast.c (ffffffff8190887c)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff8190c622)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff819104c1)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff8191d90c)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938791)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81940cce)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81944a24)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a70f)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff8194fbba)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:lookup_nexthop
```
```
In lib/dec_and_lock.c (ffffffff81971df7)
Location: arch/x86/include/asm/atomic.h:261
Inline: True
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
In arch/x86/events/core.c (ffffffff81006b33)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff81039bd7)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103fed1)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/cred.c (ffffffff810b5a25)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bac95)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810cd6c9)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810e47d5)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810ea831)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810f0667)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810fad0f)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8112a945)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8112ea70)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81162795)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffffffff811b5554)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/events/core.c (ffffffff811de8e7)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811e2e6f)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811e5179)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811ecea8)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff81202c2f)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81208523)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81226b68)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/rmap.c (ffffffff8123ff14)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8124c5fa)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8125857f)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8125f3f9)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff819e668b)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81270a71)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81278eb2)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8127e749)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81288236)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff81290edf)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff8129c9e6)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff812f010b)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff813180a9)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8131d983)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff81321f8d)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81326534)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/mount.c (ffffffff8132b043)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff8132cf70)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/ext4/balloc.c (ffffffff813368d7)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813490a5)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81365e17)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81386fc1)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In lib/syscall.c (ffffffff814f0320)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff814f9d85)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8152167e)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d7185)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d2e5)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8163131f)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/iommu/intel-svm.c (ffffffff8167599d)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8167f13d)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81690206)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff816e9f78)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff817335fc)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817345c7)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81758ff1)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8176105f)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176e2ee)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7da3)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db302)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db58e)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825f6d)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8183cf6a)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ed65)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b533)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81874930)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187bd8e)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8189429c)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818a12cb)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818b30ae)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff818c85fd)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff818e14e3)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818e61b0)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff818eab5c)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff818ebd68)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef66d)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191023a)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e84)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916a21)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8191c012)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921b78)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81923ea2)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819402d7)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa36)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff81955f7f)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819566ac)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81963acd)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff8196545b)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819783b2)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81991600)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999bbe)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff8199d5e2)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3a2a)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff819a8a5e)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In lib/dec_and_lock.c (ffffffff819ce1b0)
Location: include/asm-generic/atomic-instrumented.h:87
Inline: True
```
</details>
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
