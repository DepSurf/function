# Function: <code>arch_test_and_clear_bit</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a525)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff810168a5)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810250d5)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103c8d5)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104329b)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c8e5)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058b52)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e20)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d81)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/softirq.c (ffffffff810a1536)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110b7f4)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff811158c2)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81116832)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81122089)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8113c495)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113dbe2)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff8120efa8)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81212d31)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff81221a0b)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff8122443b)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8122bfea)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8123a60e)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff81258492)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8125eb29)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff81264bfe)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81a9586c)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/swap_state.c (ffffffff8127742b)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812a1368)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a3abc)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812ba493)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff8130fe01)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81350653)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813586d4)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813d8134)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813dc461)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8140a7af)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814163fe)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8142aaa1)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8142b6d5)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8149be26)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814db1dc)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff814fa7ff)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81550dfc)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81555619)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81556612)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815c32b6)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e5a2)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81651912)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8166819e)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8166ec5b)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816975cb)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816d31c4)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff816e2cbc)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8172cf43)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81739490)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81751371)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff81758248)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff8179d416)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817b9ae1)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817c9f79)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180e9cb)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182db9d)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185cf4d)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff818693ac)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff81874039)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818b1ae2)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818da848)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff818fa79b)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff81957c35)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a6dd1e)
Location: arch/x86/include/asm/bitops.h:161
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff8100aae5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017255)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810256b5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103d095)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810439fb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d2a5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059422)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078e90)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81087a71)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a4584)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810a7af6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81117af4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff81121d13)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81122c02)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8112e6a9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811480a5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81149792)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff8121c258)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81220581)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8122f4bb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff812321cb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81239eaf)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8124891e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff81266962)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8126d33a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8127348e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81acd14f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff812853ae)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81286f0b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812b2788)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b4fbc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812cbbc3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81322dd1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813688e3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff81370924)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813f2214)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813f64b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81423fe8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81430303)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814447f1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81445425)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814b5eff)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814f460c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8151875f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157229c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81576c59)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81577c32)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815e44fb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660b12)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673ee7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8168a8ee)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8169126b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ba15b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816f70a6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff81706e6c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff81750f61)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8175d1e0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81775601)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffffffff817c0eb6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817ea331)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817faa9b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183fadb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185f4cd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188ec83)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff8189b14c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff818a5e49)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818e3f72)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff8190c998)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8192c8db)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff8198e0d5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aa46ee)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff8100bd5b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018705)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027bb5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103ff35)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104729b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051fb5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e7cf)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108017c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81089ef0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810ab854)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810af5a1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81123305)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_wait_for_interrupt
  - kernel/irq/manage.c:irq_wait_for_interrupt
```
```
In kernel/irq/affinity.c (ffffffff8112dfd6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112f24d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8113c859)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff81157ee5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811597a4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81247017)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff8124cb50)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/filemap.c (ffffffff8124d9a1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/page-writeback.c (ffffffff8125c5a4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff8125f41b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81263d62)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/backing-dev.c (ffffffff8127689e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/mlock.c (ffffffff81296bf1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8129d53a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812a4563)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81bc5b44)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff812b7843)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812b948b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812e7d27)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812ea4cc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff813025e2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/buffer.c (ffffffff8135d840)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813b0bb1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813b8de7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8143f58b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81443a41)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff814733fe)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81480818)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff81495851)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81496591)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff815157af)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81554c8c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff81578af0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816167fc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8161b539)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8161c912)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff8168fb9b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8170fb72)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81724df8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c89e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81743a3b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176eaab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817b021c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817c1c18)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8180fbb6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8181cb04)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81838532)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff8188094b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8188a716)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818b9636)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff818cad3b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191243d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819325ed)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d923)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff8196a6b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff81975d9d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff819b7462)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff819de708)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff819fff9b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff81a645e5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a83b1a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ba018b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81bacbae)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
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
In arch/x86/events/amd/ibs.c (ffffffff8100ad0f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018de0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027aa5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103fe75)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81046af0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810510d5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ccef)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fd9c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a170)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a70d4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810aad35)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111f145)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_wait_for_interrupt
  - kernel/irq/manage.c:irq_wait_for_interrupt
```
```
In kernel/irq/affinity.c (ffffffff81129bc6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112b1d1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81136f69)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff81153fd5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81155744)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81251664)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff81256f94)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/filemap.c (ffffffff81257ef1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/page-writeback.c (ffffffff81266950)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff81269a1b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8127019a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/backing-dev.c (ffffffff8128119e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff8128cbcd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a1a2f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff812a894b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812af4f4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812c2784)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812c4e23)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812f3113)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812f5658)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8130e3c3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/buffer.c (ffffffff8136b430)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813c21b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813ca82f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8145b7eb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff8145fb21)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8148ddd0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8149befb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814b32b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff814b400a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff81532700)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81571433)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8159568f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b535)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163d19d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81641ca9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81642ee2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff816ad64b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172c5b0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81741cad)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81758a0e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8175fb22)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817893ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817c4ddd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817d6e38)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8181eaf6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8182c195)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848eb2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff8188f10b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81898846)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818c7f16)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff818d5e2b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81919aa2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193984d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81964323)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81971231)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff8197ad8d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff819b9962)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff819de148)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff819fffdb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81a6c725)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a8d64a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bafb6b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81bbf745)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In arch/x86/events/amd/ibs.c (ffffffff8100b69e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a100)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a145)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81041805)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81048520)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810528a5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d64f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080e5c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8108add0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a8174)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810ab755)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111f524)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff81129e62)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112bb0a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81137c39)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff8115544c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81156af0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff8125785d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/watch_queue.c (ffffffff8125b424)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/filemap.c (ffffffff8125c4d1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/page-writeback.c (ffffffff8126b3fe)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff8126d80b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81275f8d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff812862ce)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff81291a22)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a71eb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff812addf8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812b49e8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812c960a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812cbac3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812f94ac)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812fbc94)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8131499c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/buffer.c (ffffffff81371cd0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813c8d71)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813d189d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8146112a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81465201)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff814936bf)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814a100d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814b90f1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff814b9e3a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8153aaba)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81579463)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff8157e1e7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff8159c2e3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161ebab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81620cfd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81624b89)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81625d02)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff81646ff0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff8168fbcb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710300)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81725660)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c8ae)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81743984)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176cb2b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817a7c38)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817ba858)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff818019be)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8180f49d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182c2e5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81871a4b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8187af8a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818ab586)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff818b936b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fcb14)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191cf6d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948743)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81955321)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff8195efbd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff8199e152)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff819c4158)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff819e653b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81a54eb5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a761ba)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9eca7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81baf29f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_flush_join_list
```
```
In net/mptcp/subflow.c (ffffffff81bb11d5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In arch/x86/events/amd/ibs.c (ffffffff8100bb93)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101c990)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102e735)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81047aa5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104ee60)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105ae65)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066d60)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fdcc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a370)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810b9c24)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810bd0d5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff8113f99f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8114a7a5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8114c667)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8115a989)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff811798ff)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8117b870)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812910f9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff81297232)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/filemap.c (ffffffff81298384)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a80b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff812a9e7b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b260b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff812c5559)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff812d12e9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812e8704)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff812ef56e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812f65c8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff8130e630)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81310bb2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff8133e525)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81345a89)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81360f71)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/buffer.c (ffffffff813c0cf0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io-wq.c (ffffffff813f0fde)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_hash_wake
```
```
In fs/quota/dquot.c (ffffffff81419587)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff81422d9d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff814b660d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff814bab81)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff814eab1f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814f90bd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff81511921)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8151266a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8159946c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff815de6a3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff815e38e7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff81604ab6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168e4db)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816902bd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff816943d9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff816954f2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff816b88a0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff81705522)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178cce0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a450a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff817bceae)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff817c44ac)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817f226b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/base/cacheinfo.c (ffffffff818446e0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e646)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/label.c (ffffffff81899a29)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b7e85)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81902187)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8190c48a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81940506)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff8194ee4b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199ba89)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bf95b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed743)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff819fa951)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff81a048fd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff81a4add2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81a733f8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81a96a6b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81b0dbc5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81b307fa)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6c327)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81c7cf9f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_flush_join_list
```
```
In net/mptcp/subflow.c (ffffffff81c7f315)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In arch/x86/events/amd/ibs.c (ffffffff8100c7af)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f340)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81033875)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81050bf5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8105a0b0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067875)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073ab0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0c8e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad4d0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810d072c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810d41d5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff81163341)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8116fc16)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff81172108)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8118423c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff811aee87)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811b0f0e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812e65eb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff812ed068)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/filemap.c (ffffffff812ee8e4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/page-writeback.c (ffffffff81300854)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/swap.c (ffffffff81303225)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f3e9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff813229ee)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff81330abc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134a928)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mmap.c (ffffffff81352a2b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8135c1a7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff81372e7e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff81377989)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8137b96e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff813b08c9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff813ba567)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff813dcd59)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8144799e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff8149000c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8149ab6a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8153fffd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81544a25)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff815796bb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81588b58)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff815a3c81)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff815a4b23)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8163e019)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff8168c845)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff81692b47)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff816b8276)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff816d9bc6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_hash_wake
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ade76)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817aeca0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff817b5239)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff817b61c1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff817dcd2c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff818338aa)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c4890)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd7f1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff818f912e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff819011cc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81932c4c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/base/cacheinfo.c (ffffffff819888c0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7935)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d90b8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff819e35dc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a034d1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81a54092)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81a6009a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81a9875b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81aa7f1b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af9266)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b20479)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b54053)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81b61e29)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c59e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9b73e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81bb9702)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81be5eea)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81c0d93b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81c94f95)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81cbb696)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e0ee17)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81e23267)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81e24cc1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In arch/x86/events/amd/ibs.c (ffffffff8100f7f0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023a30)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103b2b5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8105e155)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81067ac0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076d95)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083e50)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8a11)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7610)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810ef00c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810f3115)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff81196f81)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff811a6054)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff811a8818)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811bf4cc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef647)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811f1b4e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff813500c8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff813573e8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/filemap.c (ffffffff81358f14)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8136b151)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/swap.c (ffffffff8136f9f5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff8137e700)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff8139718e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff813a792d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c3518)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mmap.c (ffffffff813cca86)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff813d5ea8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff813f05fe)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff813f5201)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff813f92e3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/migrate.c (ffffffff8143143d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff8143cb91)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memory-failure.c (ffffffff814623a9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff814d64fe)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81523b62)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8152f0a7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff815deafd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/revoke.c (ffffffff815e3b35)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8161ed4b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8162f048)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8164d941)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8164ead3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff816f5c43)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/elevator.c (ffffffff81730d3e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister_queue
```
```
In block/blk-mq-tag.c (ffffffff8174b015)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff81750fca)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff8177872f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff817a5bf6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_hash_wake
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c7486)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c820c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff818cf559)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff818d0721)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff818ff09c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff81967536)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a150b0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30cd1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a51fbe)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81a5b0cc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81a9184c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/base/cacheinfo.c (ffffffff81af76a0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52775)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b540f8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81b5f236)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81ff1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81bdd88d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81beb81a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c1b617)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81c2ef2b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c87394)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb2799)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ceccf0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81cfc01d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff81d08670)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_unplug
  - drivers/md/md-bitmap.c:md_bitmap_unplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d08e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81d5ea32)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81d9210a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81dc10ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/sched/sch_generic.c (ffffffff81e50a65)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/ethtool/ioctl.c (ffffffff81e79c26)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe5357)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81ff9fea)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81ffc831)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In arch/x86/events/amd/ibs.c (ffffffff8100eddd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023750)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103b385)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8105f805)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81069370)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078f95)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810863f0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bbbe1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810cad60)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810fafbc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810ff455)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff811a8a91)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/matrix.c (ffffffff811ba4e8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811d1fac)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff81203df4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff812062ee)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/bpf/cpumask.c (ffffffff8135d865)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu
```
```
In kernel/events/uprobes.c (ffffffff813812a2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff81388c6f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In mm/filemap.c (ffffffff8138a871)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8139d2b3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/swap.c (ffffffff813a1b1f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813afdea)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff813ca11e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff813daf1b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813f8a1f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mmap.c (ffffffff8140135b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8140afb8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff8142418e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff814283dc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8142c077)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/migrate.c (ffffffff81466dbd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814721e7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memory-failure.c (ffffffff81496e54)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff8150ca6e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/quota/dquot.c (ffffffff8155b398)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8156735b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8161655d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/revoke.c (ffffffff8161b2f5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8165710b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff816672ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff816860f1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81687333)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8172ffaa)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_check_last_writer
```
```
In block/elevator.c (ffffffff8176cf9e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister_queue
```
```
In block/blk-mq-tag.c (ffffffff81787727)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff8178d59a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff817b830f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff817e6e96)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_wake
```
```
In lib/group_cpus.c (ffffffff818e6a8f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190a4e8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b9fe)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff819124f9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff819136b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff8194262c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff819adb06)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5e170)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a4e1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a9c2ce)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81aa5718)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81add0bc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af42)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/base/cacheinfo.c (ffffffff81b458e0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba5c35)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7648)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81bb27af)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd5d01)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81c344a1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81c43cca)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c8253c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81c9618b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d19db9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55a10)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81d63c3d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff81d71800)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7c5e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81dc96e9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81e004ba)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81e30cfb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/sched/sch_generic.c (ffffffff81eac275)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/ethtool/ioctl.c (ffffffff81ed5f26)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82061667)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff82076711)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/subflow.c (ffffffff82078b71)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In arch/x86/events/amd/ibs.c (ffffffff8101451d)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029880)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d7ee)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81041845)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81066965)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810707e0)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080665)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d2d0)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/mm/pgtable.c (ffffffff810d32b0)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8110445c)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
```
```
In kernel/softirq.c (ffffffff81108b05)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff811b85f1)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/matrix.c (ffffffff811ca3a8)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811e6c2c)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a3b4)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8121d4fe)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/bpf/cpumask.c (ffffffff81386605)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu
```
```
In kernel/events/uprobes.c (ffffffff813aa652)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff813b26cf)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
```
```
In mm/filemap.c (ffffffff813b4391)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff813c3cf5)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/swap.c (ffffffff813cb7af)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813d92d7)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff813f4aae)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff814050a9)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff814245dc)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mmap.c (ffffffff8142d9a9)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff814377b0)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff81450fb5)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff81461cc4)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff814657d4)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/migrate.c (ffffffff8149601d)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a2377)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memory-failure.c (ffffffff814c6c56)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff815416de)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/quota/dquot.c (ffffffff8159195c)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8159d8db)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8164f37d)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/revoke.c (ffffffff81654215)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81690d61)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff816a15fb)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff816c2501)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff816c3816)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff81770938)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_check_last_writer
```
```
In block/elevator.c (ffffffff817af1ce)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister_queue
```
```
In block/blk-mq-tag.c (ffffffff817c9df7)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff817cfdfa)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff817fce02)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff8182ce36)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_wake
```
```
In lib/group_cpus.c (ffffffff8192daaf)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951ff5)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8195371e)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8195a359)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8195b5f1)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff8198b8bc)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff819f7f86)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab0860)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acd031)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81aeed9e)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81af8168)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81b304bc)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5a995)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_read_and_clear_dirty
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b64540)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_read_and_clear_dirty
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70a72)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/base/cacheinfo.c (ffffffff81b9dd90)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9eb5)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb8f8)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81c06c9f)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a955)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81ce8b0f)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81cf958a)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d36e7c)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81d4ac6b)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcfad9)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c920)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81e1aba0)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
```
In drivers/md/md-bitmap.c (ffffffff81e288df)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5f98e)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81e82199)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81ebca1a)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81eef28b)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/sched/sch_generic.c (ffffffff81f6ed05)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/ethtool/ioctl.c (ffffffff81f99a89)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82134377)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff8214d310)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
```
```
In net/mptcp/subflow.c (ffffffff8214e411)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:__mptcp_sync_state
```
```
In net/handshake/tlshd.c (ffffffff8216a58b)
Location: arch/x86/include/asm/bitops.h:159
Inline: True
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100aae5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017255)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025815)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103d215)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81043b7b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d415)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058fa2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e90)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81086a71)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8109dea4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810a1416)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811100d4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8111a2f3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8111b1e2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81126c89)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811406c5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81141db2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812148a8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81218bd1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff81227b0b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff8122a81b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812324ff)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff81240f6e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff8125efb2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8126598a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8126bade)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81a6bfbf)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8127d9fe)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127f55b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812aad68)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812ad59c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c41a3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8131b3b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81360ec3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff81368f04)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813ea7f4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813eea91)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8141c5c8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814288e3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8143cdd1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8143da05)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814ae4df)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814ecbec)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff81510d3f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81567a5c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8156ba69)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8156ca42)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815d63e2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626982)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639bd7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8165036e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81656ceb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8167fbbb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816bc896)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff816cc5bc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff81705651)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817118d0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729cf1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/nvme/host/core.c (ffffffff81748631)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_scan_work
```
```
In drivers/nvme/host/pci.c (ffffffff8174ce15)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
```
```
In drivers/net/tun.c (ffffffff81785986)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817a2711)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817b2e7b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f7e8b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818144dd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834b03)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81840fcc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff8184bcc9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff81887932)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818ac998)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff818cc8db)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff8192df45)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a43a7e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff81009414)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016685)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/process.c (ffffffff8102c8c5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810331ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103ca75)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810491a2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/mm/pgtable.c (ffffffff81075701)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8108c8c4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff8108feca)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81100e04)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8110b363)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8110c252)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811196e9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff81133445)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81135112)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81207618)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff8120bde1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8121ac5b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff8121d93b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812255ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff81233f6e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff812513e2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff81257daa)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8125db7e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81a28506)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8126f896)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127137b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff8129c69f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8129e523)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812b51e3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8130bf51)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81351b63)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8135a04c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813db274)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813df511)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8140d048)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81419363)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8142d841)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8142e475)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8149eeff)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814dd13c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8150105f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815588ac)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/acpi/ec.c (ffffffff815bffab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/acpi/nfit/core.c (ffffffff815f3ecd)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_query_poison
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161b002)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/tty/tty_ioctl.c (ffffffff816307be)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8163707b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/base/cacheinfo.c (ffffffff816a78ec)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff816d90d1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816e5350)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb902)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81703111)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/nvme/host/core.c (ffffffff8172a251)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_scan_work
```
```
In drivers/nvme/host/pci.c (ffffffff8172ccb5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
```
```
In drivers/net/tun.c (ffffffff817652d6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81794551)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817a48ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bd02b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dbc0d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc193)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff8180862c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff818132e9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff8183f2b2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818668e8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8188696b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff818e7a45)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a0066e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff8100aaa5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017215)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025675)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103d055)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810439bb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d255)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810593d2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e40)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81086a21)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8109de54)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810a13c6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110dfc4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff811181e3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff811190d2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81124b79)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8113e575)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113fc62)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81212648)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81216971)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff812258ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff812285bb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8123029f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8123ed0e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff8125cd52)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8126372a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8126987e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81ad83cf)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8127b79e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127d2fb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812a8b78)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812ab3ac)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c1fb3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81318e81)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff8135e993)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813669d4)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813e7b74)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813ebe11)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81418768)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81424a83)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff81438f71)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81439ba5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814aa57f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814e8c7c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8150cdcf)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815665cc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8156a9a9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8156b982)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815d87db)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654952)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81667d27)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8167e72e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff816850ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816adf9b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816ead66)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff816fab2c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff81744421)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817506a0)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768ac1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffffffff817b5d36)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817df1b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817ef91b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183495b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185365d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81884133)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff818905fc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff8189b2f9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818d8dd2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818fd998)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8191d8db)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff8197f0d5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aaf92e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff8100aa35)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017455)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810260f5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103e0e5)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81044dbb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e665)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a872)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079f2e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81088b51)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a5d44)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/softirq.c (ffffffff810a9346)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81119504)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff81123873)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81124782)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8113098c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff8114b085)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8114c792)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812215c8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff812259f1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff81234bab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff8123792b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8123f6e8)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8124e43e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff8126c736)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff812730ea)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff81278b0e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81ae488a)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8128b60f)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8128cec3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812b8e98)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812bb6fc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812d2a53)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8132aab1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81373831)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8137a030)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813fd374)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff814017b1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8142f4e6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8143b913)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814500e1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81450e15)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814c2fbf)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81501c1c)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff815264af)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815804ec)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81584ea9)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81585e82)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815f269b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166ee30)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816822e7)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81698d8e)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8169f6ab)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816c83fb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817055a6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817153cc)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8175f871)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8176bb20)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81784241)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffffffff817d01a6)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817f94a1)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81809b5b)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184ec79)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186ea2d)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fbf3)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff818ac1ec)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff818b7459)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818f58f2)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff8191ea18)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8193edeb)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff819a1635)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81abbcde)
Location: arch/x86/include/asm/bitops.h:160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
</details>
</li>
</ul>

## Differences
