# Function: <code>___ratelimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff813ef390)
Location: lib/ratelimit.c:28
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:print_mce
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - kernel/signal.c:__sigqueue_alloc
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/page_alloc.c:warn_alloc_failed
  - mm/page_io.c:__swap_writepage
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/block_dev.c:__blkdev_put
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/crypto.c:ext4_page_crypto
  - fs/ext4/crypto.c:ext4_page_crypto
  - fs/ext4/crypto_fname.c:ext4_fname_encrypt
  - fs/ext4/crypto_fname.c:ext4_fname_encrypt
  - fs/ext4/crypto_fname.c:ext4_fname_decrypt
  - fs/ext4/crypto_fname.c:ext4_fname_decrypt
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ahash_wait
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:nla_parse
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff813ef390-ffffffff813ef46e: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff81435c40)
Location: lib/ratelimit.c:28
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:print_mce
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - kernel/signal.c:__sigqueue_alloc
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/trace/bpf_trace.c:tracing_func_proto
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/page_alloc.c:warn_alloc_failed
  - mm/vmscan.c:isolate_lru_page
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_fault
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__vfs_msg
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ahash_wait
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:get_request
  - lib/nlattr.c:nla_parse
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81435c40-ffffffff81435d35: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff81452c30)
Location: lib/ratelimit.c:28
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - kernel/signal.c:__sigqueue_alloc
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/trace/bpf_trace.c:tracing_func_proto
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/page_alloc.c:warn_alloc
  - mm/vmscan.c:isolate_lru_page
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_fault
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__vfs_msg
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ahash_wait
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:get_request
  - lib/swiotlb.c:map_single
  - lib/nlattr.c:nla_parse
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81452c30-ffffffff81452d25: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff818f2e30)
Location: lib/ratelimit.c:28
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:print_mce
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/trace/bpf_trace.c:tracing_func_proto
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/vmscan.c:isolate_lru_page
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__vfs_msg
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ahash_wait
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:get_request
  - lib/swiotlb.c:map_single
  - lib/nlattr.c:nla_parse
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff818f2e30-ffffffff818f2f35: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff81979290)
Location: lib/ratelimit.c:28
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:print_mce
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/futex.c:futex_wake_op
  - kernel/trace/bpf_trace.c:tracing_func_proto
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/vmscan.c:isolate_lru_page
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/block_dev.c:__blkdev_put
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:get_request
  - lib/swiotlb.c:map_single
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81979290-ffffffff81979395: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (0)
Location: lib/ratelimit.c:28
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:print_mce
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:map_single
  - kernel/futex.c:do_futex
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/vmscan.c:isolate_lru_page
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/block_dev.c:__blkdev_put
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:get_request
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff819d5a5e-ffffffff819d5a79: ___ratelimit.cold.1 (STB_LOCAL)
ffffffff819d5970-ffffffff819d5a5e: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff81a0dbca)
Location: lib/ratelimit.c:28
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/vmscan.c:isolate_lru_page
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/block_dev.c:__blkdev_put
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/acpi/apei/ghes.c:__ghes_peek_estatus
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81a0dc8e-ffffffff81a0dca9: ___ratelimit.cold.1 (STB_LOCAL)
ffffffff81a0dba0-ffffffff81a0dc8e: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff81a7d52c)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_max_handler
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handler_chain
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81a7d606-ffffffff81a7d623: ___ratelimit.cold (STB_LOCAL)
ffffffff81a7d500-ffffffff81a7d606: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff81ab485c)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handle_swbp
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81ab4936-ffffffff81ab4953: ___ratelimit.cold (STB_LOCAL)
ffffffff81ab4830-ffffffff81ab4936: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff815ef280)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/rseq.c:rseq_get_rseq_cs
  - mm/filemap.c:generic_file_direct_write
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/ioctl.c:ioctl_fibmap
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:end_buffer_write_sync
  - fs/block_dev.c:bdev_write_inode
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_tiocsserial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/dst.c:dst_alloc
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff815ef190-ffffffff815ef27c: ___ratelimit.part.0 (STB_LOCAL)
ffffffff815ef298-ffffffff815ef2b5: ___ratelimit.part.0.cold (STB_LOCAL)
ffffffff815ef280-ffffffff815ef298: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff816139d0)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/rseq.c:rseq_get_rseq_cs
  - mm/filemap.c:generic_file_direct_write
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/ioctl.c:ioctl_fibmap
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read_iter
  - fs/splice.c:warn_unsupported
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:end_buffer_write_sync
  - fs/block_dev.c:bdev_write_inode
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - block/blk-core.c:handle_bad_sector
  - block/blk-lib.c:__blkdev_issue_discard
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:linereq_put_event
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_tiocsserial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/dst.c:dst_alloc
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff816138e0-ffffffff816139cc: ___ratelimit.part.0 (STB_LOCAL)
ffffffff81bf4cb3-ffffffff81bf4cd0: ___ratelimit.part.0.cold (STB_LOCAL)
ffffffff816139d0-ffffffff816139e8: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff815f7030)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:resched_latency_warn
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/rseq.c:rseq_get_rseq_cs
  - mm/filemap.c:generic_file_direct_write
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:hugetlb_no_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/ioctl.c:do_vfs_ioctl
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read_iter
  - fs/splice.c:warn_unsupported
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:end_buffer_write_sync
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio_checks
  - block/blk-lib.c:__blkdev_issue_discard
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:linereq_put_event
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/dst.c:dst_alloc
  - net/core/utils.c:net_ratelimit
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff815f6f30-ffffffff815f7022: ___ratelimit.part.0 (STB_LOCAL)
ffffffff81be6bd6-ffffffff81be6bf3: ___ratelimit.part.0.cold (STB_LOCAL)
ffffffff815f7030-ffffffff815f7048: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff816647c0)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/debug.c:resched_latency_warn
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - mm/filemap.c:generic_file_direct_write
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:hugetlb_no_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:slab_out_of_memory
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/ioctl.c:do_vfs_ioctl
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read_iter
  - fs/splice.c:warn_unsupported
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:end_buffer_write_sync
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - block/bdev.c:blkdev_flush_mapping
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio_checks
  - block/blk-lib.c:__blkdev_issue_discard
  - block/bsg.c:bsg_ioctl
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:linereq_put_event
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/dst.c:dst_alloc
  - net/core/utils.c:net_ratelimit
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff816646c0-ffffffff816647b2: ___ratelimit.part.0 (STB_LOCAL)
ffffffff81cdfa29-ffffffff81cdfa46: ___ratelimit.part.0.cold (STB_LOCAL)
ffffffff816647c0-ffffffff816647d8: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (0)
Location: lib/ratelimit.c:27
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/umip.c:umip_printk
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_utility.c:resched_latency_warn
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/folio-compat.c:isolate_lru_page
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:hugetlb_no_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
  - fs/ioctl.c:do_vfs_ioctl
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read_iter
  - fs/splice.c:warn_unsupported
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:end_buffer_write_sync
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:aa_policy_admin_capable
  - security/apparmor/policy.c:aa_policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_flush_mapping
  - block/blk-core.c:submit_bio_noacct
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_update_request
  - block/bsg.c:bsg_ioctl
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:linereq_put_event
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read_iter
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/rtc/rtc-cmos.c:cmos_read_time
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/dst.c:dst_alloc
  - net/core/utils.c:net_ratelimit
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81ea61ed-ffffffff81ea6206: ___ratelimit.cold (STB_LOCAL)
ffffffff8177ea10-ffffffff8177eb17: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff8203b670)
Location: lib/ratelimit.c:27
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/umip.c:umip_printk
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_utility.c:resched_latency_warn
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:print_irq_desc
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/folio-compat.c:isolate_lru_page
  - mm/util.c:__vm_enough_memory
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:hugetlb_no_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_read
  - fs/ioctl.c:do_vfs_ioctl
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read_iter
  - fs/splice.c:warn_unsupported
  - fs/buffer.c:__find_get_block_slow
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:notify_set_filter
  - security/apparmor/lib.c:aa_parse_debug_params
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:aa_policy_admin_capable
  - security/apparmor/policy.c:aa_policy_admin_capable
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:build_unotif
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/lockdown/lockdown.c:lockdown_is_locked_down
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_flush_mapping
  - block/blk-core.c:submit_bio_noacct
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_update_request
  - block/bsg.c:bsg_ioctl
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:linereq_put_event
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read_iter
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/rtc/rtc-cmos.c:cmos_read_time
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/dst.c:dst_alloc
  - net/core/utils.c:net_ratelimit
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff8203b670-ffffffff8203b793: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff820b9b50)
Location: lib/ratelimit.c:27
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/umip.c:umip_printk
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_utility.c:resched_latency_warn
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:print_irq_desc
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/module/kmod.c:__request_module
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/rseq.c:rseq_get_rseq_cs
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/folio-compat.c:isolate_lru_page
  - mm/util.c:__vm_enough_memory
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
  - mm/hugetlb.c:hugetlb_no_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/slub.c:slab_out_of_memory
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memfd.c:__do_sys_memfd_create
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_read
  - fs/ioctl.c:do_vfs_ioctl
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read_iter
  - fs/splice.c:warn_unsupported
  - fs/buffer.c:__find_get_block_slow
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/lockdown/lockdown.c:lockdown_is_locked_down
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_flush_mapping
  - block/blk-core.c:submit_bio_noacct
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_update_request
  - block/bsg.c:bsg_ioctl
  - block/blk-crypto.c:blk_crypto_evict_key
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:linereq_put_event
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read_iter
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:iommu_poll_ppr_log
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/init.c:amd_iommu_restart_ga_log
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/rtc/rtc-cmos.c:cmos_read_time
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff820b9b50-ffffffff820b9c73: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffff82194460)
Location: lib/ratelimit.c:27
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/umip.c:umip_printk
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/cet.c:do_user_cp_fault
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_utility.c:resched_latency_warn
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:print_irq_desc
  - kernel/irq/dummychip.c:print_irq_desc
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/module/kmod.c:__request_module
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/rseq.c:rseq_get_rseq_cs
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/folio-compat.c:isolate_lru_page
  - mm/util.c:__vm_enough_memory
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/slub.c:slab_out_of_memory
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
  - mm/hugetlb.c:hugetlb_no_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memfd.c:__do_sys_memfd_create
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_read
  - fs/ioctl.c:do_vfs_ioctl
  - fs/dcache.c:d_splice_alias
  - fs/seq_file.c:seq_read_iter
  - fs/splice.c:warn_unsupported
  - fs/buffer.c:__find_get_block_slow
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/ecryptfs/inode.c:__ecryptfs_get_inode
  - fs/pstore/platform.c:decompress_record
  - fs/efivarfs/file.c:efivarfs_file_read
  - fs/efivarfs/super.c:efivarfs_statfs
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/lockdown/lockdown.c:lockdown_is_locked_down
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_flush_mapping
  - block/blk-core.c:submit_bio_noacct
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_update_request
  - block/bsg.c:bsg_ioctl
  - block/blk-crypto.c:blk_crypto_evict_key
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:linereq_put_event
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:pci_doe_recv_resp
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/acpi/apei/ghes.c:__ghes_check_estatus
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:tty_set_serial
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485_delays
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/char/random.c:urandom_read_iter
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/iommu.c:iommu_get_default_domain_type
  - drivers/iommu/iommu.c:iommu_get_default_domain_type
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/base/node.c:do_register_memory_block_under_node
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sg.c:sg_write
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/rtc/rtc-cmos.c:cmos_read_time
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/i2c/i2c-core-base.c:i2c_check_for_quirks
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-ioctl.c:table_clear
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff82194460-ffffffff82194583: ___ratelimit (STB_GLOBAL)
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
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffff800010d8ed48)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/arm64/kernel/traps.c:arm64_show_signal
  - arch/arm64/kernel/efi.c:efi_handle_corrupted_x18
  - arch/arm64/kernel/armv8_deprecated.c:compat_setend_handler
  - arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler
  - arch/arm64/kernel/armv8_deprecated.c:swp_handler
  - arch/arm64/mm/fault.c:__do_kernel_fault
  - virt/kvm/arm/arm.c:kvm_arch_init
  - arch/arm64/kvm/handle_exit.c:handle_exit
  - arch/arm64/kvm/handle_exit.c:kvm_handle_unknown_ec
  - arch/arm64/kvm/sys_regs.c:write_to_read_only
  - arch/arm64/kvm/sys_regs.c:read_from_write_only
  - arch/arm64/kvm/sys_regs.c:print_sys_reg_instr
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_populate_lr
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_populate_lr
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handler_chain
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_wait_for_range_completion
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/iommu/virtio-iommu.c:viommu_event_handler
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/arm_sdei.c:sdei_event_handler
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_init
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffff800010d8ed48-ffff800010d8eea4: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (c0e8953c)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handle_swbp
  - kernel/rseq.c:rseq_ip_fixup
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/slub.c:slab_out_of_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/pstore/ram.c:ramoops_pstore_write
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_wait_for_range_completion
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_entry
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/regulator/ti-abb-regulator.c:ti_abb_get_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_get_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_clear_all_txdone
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_set_opp
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_isr
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
c0e8953c-c0e8964c: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (c000000000ed1b60)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/traps.c:altivec_assist_exception
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:show_signal_msg
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
  - arch/powerpc/kernel/rtas-rtc.c:rtas_set_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_boot_time
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/platforms/pseries/lpar.c:process_dtl_buffer
  - arch/powerpc/platforms/pseries/lpar.c:update_vcpu_disp_stat
  - arch/powerpc/platforms/pseries/lpar.c:update_vcpu_disp_stat
  - arch/powerpc/platforms/pseries/lpar.c:update_vcpu_disp_stat
  - arch/powerpc/platforms/pseries/lpar.c:update_vcpu_disp_stat
  - arch/powerpc/platforms/pseries/lpar.c:update_vcpu_disp_stat
  - arch/powerpc/platforms/pseries/dlpar.c:handle_dlpar_errorlog
  - arch/powerpc/perf/hv-24x7.c:make_24x7_request
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handle_swbp
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
c000000000ed1b60-c000000000ed1ce4: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ratelimit.c (ffffffe0008b770a)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/core.c:perf_duration_warn
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/irqchip/irq-sifive-plic.c:plic_handle_irq
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffe0008b770a-ffffffe0008b77ca: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff81a536ac)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handle_swbp
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:nvme_cancel_request
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81a53786-ffffffff81a537a3: ___ratelimit.cold (STB_LOCAL)
ffffffff81a53680-ffffffff81a53786: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff81a10798)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handle_swbp
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/nvdimm/btt.c:btt_read_pg
  - drivers/nvdimm/btt.c:btt_map_read
  - drivers/dax/device.c:check_vma
  - drivers/dax/device.c:check_vma
  - drivers/dax/device.c:check_vma
  - drivers/dax/device.c:check_vma
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:nvme_cancel_request
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81a10866-ffffffff81a10883: ___ratelimit.cold (STB_LOCAL)
ffffffff81a10780-ffffffff81a10866: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff81abfa9c)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handle_swbp
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/netfilter/nf_conntrack_timeout.c:nf_ct_set_timeout
  - net/netfilter/nf_conntrack_timeout.c:nf_ct_set_timeout
  - net/netfilter/nf_conntrack_timeout.c:nf_ct_set_timeout
  - net/netfilter/nf_conntrack_timeout.c:nf_ct_set_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81abfb76-ffffffff81abfb93: ___ratelimit.cold (STB_LOCAL)
ffffffff81abfa70-ffffffff81abfb76: ___ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ___ratelimit(struct ratelimit_state *rs, const char *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/ratelimit.c (ffffffff81acbf6c)
Location: lib/ratelimit.c:27
Inline: True
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:warn_bad_vsyscall
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/nmi.c:nmi_handle
  - arch/x86/kernel/cpu/mce/core.c:print_mce
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/umip.c:umip_printk
  - kernel/panic.c:refcount_error_report
  - kernel/signal.c:__sigqueue_alloc
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/printk/printk.c:__printk_ratelimit
  - kernel/printk/printk.c:devkmsg_write
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/futex.c:futex_wake_op
  - kernel/events/core.c:perf_duration_warn
  - kernel/events/uprobes.c:handle_swbp
  - kernel/rseq.c:rseq_ip_fixup
  - mm/oom_kill.c:oom_kill_process
  - mm/vmscan.c:isolate_lru_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:warn_alloc
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_no_page
  - mm/slub.c:slab_out_of_memory
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - fs/dcache.c:d_splice_alias
  - fs/buffer.c:buffer_io_error
  - fs/block_dev.c:__blkdev_put
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/crypto/crypto.c:fscrypt_msg
  - fs/verity/init.c:fsverity_msg
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat__get_entry
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/crypto.c:init_profile_hash
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - block/blk-core.c:blk_update_request
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_kick_worker
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/char/random.c:urandom_read
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_write_bvec
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/ata/libata-core.c:ata_ratelimit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/i2c/i2c-core-base.c:i2c_quirk_error
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - net/core/dev.c:validate_xmit_skb
  - net/core/utils.c:net_ratelimit
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff81acc046-ffffffff81acc063: ___ratelimit.cold (STB_LOCAL)
ffffffff81acbf40-ffffffff81acc046: ___ratelimit (STB_GLOBAL)
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
