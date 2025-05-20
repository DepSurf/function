# Function: <code>test_and_clear_bit</code>

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
In arch/x86/events/amd/ibs.c (ffffffff810091cd)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100eced)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100f2c2)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014f75)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015f06)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_notifier
```
```
In arch/x86/xen/mmu.c (ffffffff810203d5)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff810392ed)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103deb6)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044b05)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064e40)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81070fde)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/softirq.c (ffffffff8108523f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/kthread.c (ffffffff810a0759)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810dbbcf)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/tick-broadcast.c (ffffffff810fd5de)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff810fef30)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81188d88)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff8118c4b7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81198cdb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/vmscan.c (ffffffff811a3382)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/vmstat.c (ffffffff811ad16f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff811ae124)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/mlock.c (ffffffff811c2e3a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:munlock_vma_page
```
```
In mm/mmap.c (ffffffff811c82e0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff811cabc7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/swap_state.c (ffffffff811d2a99)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff811f1c43)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memory-failure.c (ffffffff81201cc0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81244fd7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
```
```
In fs/quota/dquot.c (ffffffff812715ef)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/proc/task_mmu.c (ffffffff81278e25)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff812e7357)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
```
```
In fs/jbd2/revoke.c (ffffffff812edad9)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81312edb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_readdir
```
```
In security/keys/gc.c (ffffffff8132efc1)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8132f5de)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_reject_and_link
```
```
In block/blk-mq.c (ffffffff813c342a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_work_fn
```
```
In block/blk-mq-tag.c (ffffffff813c75cc)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81427fa2)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
```
```
In drivers/pwm/core.c (ffffffff8142c79e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_put
```
```
In drivers/pwm/sysfs.c (ffffffff8142d437)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:unexport_store
```
```
In drivers/tty/n_tty.c (ffffffff814e4e3f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/tty/tty_ioctl.c (ffffffff814e844e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/tty_port.c (ffffffff814eb18c)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/sysrq.c (ffffffff814ee27d)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_core.c (ffffffff81501d65)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/scsi/scsi_lib.c (ffffffff815b11b7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff815b7b97)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff815ee19e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81607f8e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_event
```
```
In drivers/usb/core/devio.c (ffffffff81619b0b)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8165cbba)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8166ffdd)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8168b047)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
```
In drivers/md/md.c (ffffffff8168fce0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_start_sync
```
```
In drivers/md/bitmap.c (ffffffff8169dd98)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/socket.c (ffffffff816fd0cf)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81713929)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:netif_wake_subqueue
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:napi_complete_done
```
```
In net/core/flow.c (ffffffff817352bb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/sched/sch_generic.c (ffffffff81741805)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81774a22)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
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
In arch/x86/events/amd/ibs.c (ffffffff810096c9)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100e1d7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015357)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_cpu_dying
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_exit_boxes
```
```
In arch/x86/xen/mmu.c (ffffffff810203c5)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81038311)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103dcd6)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044b75)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064bf4)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810709a9)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/softirq.c (ffffffff810883dc)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/kthread.c (ffffffff810a3e49)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e144e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/time/tick-broadcast.c (ffffffff8110494e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811062ae)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff8119b457)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff8119faa7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/oom_kill.c (ffffffff811a4f79)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In mm/page-writeback.c (ffffffff811b0b50)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811b9a97)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff811c7544)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff811deb08)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff811e441c)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff811e7bad)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/swap_state.c (ffffffff811f0819)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812132dc)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812166cb)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81227866)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8126dbb7)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff8129f797)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff812a57ee)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff81317194)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff8131b370)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81347a59)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In security/keys/gc.c (ffffffff81363c91)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81364613)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In block/blk-mq.c (ffffffff81408f85)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_work_fn
```
```
In block/blk-mq-tag.c (ffffffff8140b80c)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8147397a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8147775e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_put
```
```
In drivers/pwm/sysfs.c (ffffffff81478613)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:unexport_store
```
```
In drivers/tty/tty_ioctl.c (ffffffff8153959e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8153ecd4)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/scsi/scsi_lib.c (ffffffff81609424)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff81610427)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff8164d28e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8166a380)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81679d26)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816bd42a)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816d032d)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec477)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff816f71a0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
```
```
In drivers/md/bitmap.c (ffffffff81700254)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_daemon_work
```
```
In net/socket.c (ffffffff81763c2e)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8177b599)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_wake_subqueue
```
```
In net/core/flow.c (ffffffff817a1442)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/sched/sch_generic.c (ffffffff817ae695)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff817e19a2)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ncsi/ncsi-rsp.c (ffffffff8188d77f)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff8188e9b0)
Location: arch/x86/include/asm/bitops.h:250
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_remove_filter
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
In arch/x86/events/amd/ibs.c (ffffffff81009709)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100e297)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015450)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu.c (ffffffff81020a75)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81037dc1)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103d59b)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81043094)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810467f5)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810680c0)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81074639)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In kernel/softirq.c (ffffffff8108d40c)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/kthread.c (ffffffff810a94ce)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/irq/manage.c (ffffffff810e77df)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff810efd01)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c095)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8110da20)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff811aae4b)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff811afd34)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff811c1136)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811ca122)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff811d7664)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff811ee928)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff811f445d)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff811f8f2d)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/swap_state.c (ffffffff81201210)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff81225644)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81228c70)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81239df0)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81280e07)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff812b5af8)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff812bb138)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8132d184)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81331360)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8135d3a5)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In security/keys/gc.c (ffffffff8137a4b1)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8137ae33)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In block/blk-mq.c (ffffffff81423955)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_work_fn
```
```
In block/blk-mq-tag.c (ffffffff81425e5c)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81495b9a)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81498abe)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_put
```
```
In drivers/pwm/sysfs.c (ffffffff81499925)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff814f3b82)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/acpi/ec.c:__acpi_ec_disable_event
```
```
In drivers/tty/tty_ioctl.c (ffffffff81565cae)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8156b324)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/base/cacheinfo.c (ffffffff815d2b2f)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/scsi/scsi_lib.c (ffffffff81638d04)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff8163fcb7)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff8167efce)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff816980b0)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff816a7a06)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816eb31c)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816fe20d)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d467)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81728a1a)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/bitmap.c (ffffffff81731f86)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff817639b6)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81790c5e)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff817a8c09)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:netif_tx_wake_queue
  - net/core/dev.c:netif_wake_subqueue
```
```
In net/core/flow.c (ffffffff817cfd60)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/sched/sch_generic.c (ffffffff817ddd25)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff818c192f)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c2ca0)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_remove_filter
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
In arch/x86/events/amd/ibs.c (ffffffff810093ce)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013970)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020d15)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81035c9e)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103b5eb)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104135d)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810464b5)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810673e0)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810740ae)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/softirq.c (ffffffff8108a43c)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/kthread.c (ffffffff810a61b6)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/irq/manage.c (ffffffff810e722f)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff810efcd8)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/livepatch/transition.c (ffffffff810f8e09)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff8110e445)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8110f920)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff811b245f)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff811b58e1)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff811c939f)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811d2b1a)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff811e07be)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/mlock.c (ffffffff811f9930)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff811ff3dd)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff81203043)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/swap_state.c (ffffffff8120c08b)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff81230c97)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812322a8)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81245aae)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8128e6e7)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff812c2c5a)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff812c66e1)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff81342354)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813462c4)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81371d84)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In security/keys/gc.c (ffffffff8138e093)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8138ea16)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In block/blk-mq.c (ffffffff8143004b)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff81433a0c)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-mq-sched.c (ffffffff8143545d)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149f5c9)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff814a2db9)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff814a3565)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff81502383)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/tty/tty_ioctl.c (ffffffff8157927e)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8157facd)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/lightnvm/core.c (ffffffff815d81e3)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff815e76a1)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164d763)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff8165471b)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff8169429e)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff816ad8b1)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff816bcbb6)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816ff98a)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817136fa)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8173562d)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff817411e8)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/bitmap.c (ffffffff8174ae4c)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff81781fb6)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff817ae58a)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff817ca06a)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:netif_tx_wake_queue
```
```
In net/core/flow.c (ffffffff817ef15e)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/sched/sch_generic.c (ffffffff817fd345)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff818e82af)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff818e9647)
Location: arch/x86/include/asm/bitops.h:263
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_remove_filter
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
In arch/x86/events/amd/ibs.c (ffffffff81009afe)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff810141b0)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810218c2)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81037fa2)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103e00b)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104474d)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049ce9)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b630)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81079ba3)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/softirq.c (ffffffff810914fc)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/kthread.c (ffffffff810ac75b)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unpark
```
```
In kernel/irq/manage.c (ffffffff810ef516)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff810f88a5)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff810f92be)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81103829)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff811196c5)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8111ac00)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff811c6075)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff811c99d1)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff811de1ae)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/vmscan.c (ffffffff811e804e)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff811f67b2)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/mlock.c (ffffffff81211d5c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff812179dd)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8121c4d3)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/swap_state.c (ffffffff812256c8)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff8124e9f1)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812531b4)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81265a61)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff812b12d7)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff812e478c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff812ecc52)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff81366984)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff8136a954)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81396a84)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In security/keys/gc.c (ffffffff813b3531)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff813b3ef6)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In block/blk-mq.c (ffffffff8145c35c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8145f6d0)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-mq-sched.c (ffffffff81461239)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814de10f)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff814e1b29)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff814e22dc)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815446d3)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/tty/tty_ioctl.c (ffffffff815ddc2e)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff815e464d)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81609ec2)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff8163ee33)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff8164ea51)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b6a33)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff816bdc6b)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff816fe293)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81718a47)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81728586)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8176c51f)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8178493a)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a732d)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff817b32f1)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff817bd1b1)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff817f8356)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff8182665a)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8184398a)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:netif_tx_wake_queue
```
```
In net/sched/sch_generic.c (ffffffff8187ad9a)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff8196ebc7)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_remove_filter
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
In arch/x86/events/amd/ibs.c (ffffffff8100a0fd)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014cf2)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022365)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81039162)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8103f5bb)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810436a7)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104696a)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c2b5)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106e300)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c6fd)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/softirq.c (ffffffff81094f86)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810f78f6)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8110098e)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8110180e)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8110c558)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff81126235)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81127960)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff811e6439)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff811eab31)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff811ff7de)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff81201dfb)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81209709)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff81217a92)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff81232a87)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff81238d39)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8123e30c)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/swap_state.c (ffffffff81247c7c)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff81272820)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81277654)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81289e13)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff812d913a)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81311e92)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff81319292)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff81395064)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81399091)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff813c5c5e)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In security/keys/gc.c (ffffffff813e3c71)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff813e45c5)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff81451410)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81492fad)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-mq-sched.c (ffffffff81494c59)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In block/blk-zoned.c (ffffffff814b7faf)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150d29c)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81511319)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81511af5)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff8157a733)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/tty/tty_ioctl.c (ffffffff81616eee)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8161d656)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816436df)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff8167a1dc)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff8168a1a5)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f2d24)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff816fa248)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff8173c3c3)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81757c29)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817673d6)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a83ea)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c5a0a)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817eee4c)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff817fae7d)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff81805298)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff81841952)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff8186fd8a)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8188dd3b)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:netif_tx_wake_queue
```
```
In net/sched/sch_generic.c (ffffffff818cd135)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff819c664e)
Location: arch/x86/include/asm/bitops.h:265
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff8100a02d)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015402)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021cf5)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103a315)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81040bbb)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810499a5)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810558fb)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810742d0)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8108310d)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/softirq.c (ffffffff8109cdb6)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110316d)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8110c14d)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8110d12b)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81117d48)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff81131915)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81133050)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff811f6f89)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff811fb6a1)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff812120ae)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffff8121477b)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8121c3e9)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8122a9a2)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff81246257)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8124c6f9)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8125289c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/swap_state.c (ffffffff8125c250)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff81286dd8)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81288e51)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8129ed85)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff812ee60a)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81328a12)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813308aa)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813addd4)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813b1e01)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff813def26)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff813ea10c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/keys/gc.c (ffffffff813fe461)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff813fedb5)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8146e558)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814acecd)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff814cbf5f)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815228dc)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81526a29)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff815271d1)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815923b3)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a5c0)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/tty/tty_ioctl.c (ffffffff816340ee)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8163a8bf)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81661a0f)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff81698c0c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff816a96a5)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff816f3b9f)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715bc4)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff8171cc88)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff8175fd03)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8177c199)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff8178b966)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817ce39c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ecfda)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181ad1c)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81826f14)
Location: arch/x86/include/asm/bitops.h:264
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
In drivers/md/md-bitmap.c (ffffffff81831498)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff8186d872)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff8189095a)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff818aebcb)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:netif_tx_wake_queue
```
```
In net/sched/sch_generic.c (ffffffff818f8495)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff819fddae)
Location: arch/x86/include/asm/bitops.h:264
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff8100a525)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff810168a5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810250d5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103c8d5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104329b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c8e5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058b52)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e20)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d81)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/softirq.c (ffffffff810a1536)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110b7f4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff811158c2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81116832)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81122089)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8113c495)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113dbe2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff8120efa8)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81212d31)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff81221a0b)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8122bfea)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8123a60e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff81258492)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8125eb29)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff81264bfe)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81a9586c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/swap_state.c (ffffffff8127742b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812a1368)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812ba493)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff8130fe01)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81350653)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813586d4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813d8134)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813dc461)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8140a7af)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814163fe)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8142aaa1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8142b6d5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8149be26)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814db1dc)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff814fa7ff)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81550dfc)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81555619)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81556612)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815c32b6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e5a2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81651912)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8166819e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8166ec5b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816975cb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816d31c4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff816e2cbc)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8172cf43)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81739490)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81751371)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/scsi/scsi_logging.c (ffffffff81758248)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_release_buffer
```
```
In drivers/net/tun.c (ffffffff8179d416)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817b9ae1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817c9f79)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180e9cb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182db9d)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185cf4d)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff818693ac)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818b1ae2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818da848)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff818fa79b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff81957c35)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a6dd1e)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017255)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810256b5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103d095)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810439fb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d2a5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059422)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078e90)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81087a71)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a4584)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/softirq.c (ffffffff810a7af6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81117af4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff81121d13)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81122c02)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8112e6a9)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811480a5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81149792)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff8121c258)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81220581)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8122f4bb)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81239eaf)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8124891e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff81266962)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8126d33a)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8127348e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81acd14f)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff812853ae)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81286f0b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812b2788)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812cbbc3)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813688e3)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff81370924)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813f2214)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813f64b1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81423fe8)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81430303)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814447f1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81445425)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814b5eff)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814f460c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8151875f)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157229c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81576c59)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81577c32)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815e44fb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660b12)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673ee7)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8168a8ee)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8169126b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ba15b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816f70a6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff81706e6c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff81750f61)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8175d1e0)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81775601)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffffffff817c0eb6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817ea331)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817faa9b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183fadb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185f4cd)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188ec83)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff8189b14c)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818e3f72)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff8190c998)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8192c8db)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff8198e0d5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aa46ee)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018705)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027bb5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103ff35)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104729b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051fb5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e7cf)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108017c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81089ef0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810ab854)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In kernel/softirq.c (ffffffff810af5a1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81123305)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_wait_for_interrupt
  - kernel/irq/manage.c:irq_wait_for_interrupt
```
```
In kernel/irq/affinity.c (ffffffff8112dfd6)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112f24d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8113c859)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff81157ee5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811597a4)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81247017)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff8124cb50)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/filemap.c (ffffffff8124d9a1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/page-writeback.c (ffffffff8125c5a4)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81263d62)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/backing-dev.c (ffffffff8127689e)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/mlock.c (ffffffff81296bf1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8129d53a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812a4563)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81bc5b44)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff812b7843)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812b948b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812e7d27)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff813025e2)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813b0bb1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813b8de7)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8143f58b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81443a41)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff814733fe)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81480818)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff81495851)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81496591)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff815157af)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81554c8c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff81578af0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816167fc)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8161b539)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8161c912)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff8168fb9b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8170fb72)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81724df8)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c89e)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81743a3b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176eaab)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817b021c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817c1c18)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8180fbb6)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8181cb04)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81838532)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff8188094b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8188a716)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818b9636)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff818cad3b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191243d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819325ed)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d923)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff8196a6b1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff819b7462)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff819de708)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff819fff9b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff81a645e5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a83b1a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ba018b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81bacbae)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018de0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027aa5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103fe75)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81046af0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810510d5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ccef)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fd9c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a170)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a70d4)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In kernel/softirq.c (ffffffff810aad35)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111f145)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_wait_for_interrupt
  - kernel/irq/manage.c:irq_wait_for_interrupt
```
```
In kernel/irq/affinity.c (ffffffff81129bc6)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112b1d1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81136f69)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff81153fd5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81155744)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81251664)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff81256f94)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/filemap.c (ffffffff81257ef1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/page-writeback.c (ffffffff81266950)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8127019a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/backing-dev.c (ffffffff8128119e)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff8128cbcd)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a1a2f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812af4f4)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812c2784)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812c4e23)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812f3113)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8130e3c3)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/buffer.c (ffffffff8136b430)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813c21b1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813ca82f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8145b7eb)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff8145fb21)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8148ddd0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8149befb)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814b32b1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff814b400a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff81532700)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81571433)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8159568f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b535)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163d19d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81641ca9)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81642ee2)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff816ad64b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172c5b0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81741cad)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81758a0e)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8175fb22)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817893ab)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817c4ddd)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817d6e38)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8181eaf6)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8182c195)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848eb2)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff8188f10b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81898846)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818c7f16)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff818d5e2b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81919aa2)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193984d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81964323)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81971231)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff819b9962)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff819de148)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff819fffdb)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81a6c725)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a8d64a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bafb6b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81bbf745)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a100)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a145)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81041805)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81048520)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810528a5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d64f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080e5c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8108add0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a8174)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In kernel/softirq.c (ffffffff810ab755)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111f524)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff81129e62)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8112bb0a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81137c39)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff8115544c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81156af0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff8125785d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/watch_queue.c (ffffffff8125b424)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/filemap.c (ffffffff8125c4d1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/page-writeback.c (ffffffff8126b3fe)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81275f8d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff812862ce)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff81291a22)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a71eb)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812b49e8)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff812c960a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812cbac3)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812f94ac)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8131499c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/buffer.c (ffffffff81371cd0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff813c8d71)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813d189d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8146112a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81465201)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff814936bf)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814a100d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814b90f1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff814b9e3a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8153aaba)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81579463)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff8157e1e7)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff8159c2e3)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161ebab)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81620cfd)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81624b89)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81625d02)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff81646ff0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff8168fbcb)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710300)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81725660)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c8ae)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81743984)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176cb2b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817a7c38)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817ba858)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff818019be)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8180f49d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182c2e5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81871a4b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8187af8a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818ab586)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff818b936b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fcb14)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191cf6d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948743)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81955321)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff8199e152)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff819c4158)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff819e653b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81a54eb5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a761ba)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9eca7)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81baf29f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101c990)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102e735)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81047aa5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8104ee60)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105ae65)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066d60)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fdcc)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a370)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810b9c24)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In kernel/softirq.c (ffffffff810bd0d5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff8113f99f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8114a7a5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff8114c667)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8115a989)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff811798ff)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8117b870)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812910f9)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff81297232)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/filemap.c (ffffffff81298384)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a80b1)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b260b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff812c5559)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff812d12e9)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812e8704)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff812f65c8)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffff8130e630)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81310bb2)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff8133e525)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81345a89)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81360f71)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/buffer.c (ffffffff813c0cf0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io-wq.c (ffffffff813f0fde)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_hash_wake
```
```
In fs/quota/dquot.c (ffffffff81419587)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff81422d9d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff814b660d)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff814bab81)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff814eab1f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814f90bd)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff81511921)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8151266a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8159946c)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff815de6a3)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff815e38e7)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff81604ab6)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168e4db)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816902bd)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff816943d9)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff816954f2)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff816b88a0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff81705522)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178cce0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a450a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff817bceae)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff817c44ac)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817f226b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/base/cacheinfo.c (ffffffff818446e0)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e646)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/label.c (ffffffff81899a29)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b7e85)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81902187)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8190c48a)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81940506)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff8194ee4b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199ba89)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bf95b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed743)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff819fa951)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff81a4add2)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81a733f8)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81a96a6b)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81b0dbc5)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81b307fa)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6c327)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81c7cf9f)
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:81
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f340)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81033875)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81050bf5)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff8105a0b0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067875)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073ab0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0c8e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad4d0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810d072c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff810d41d5)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff81163341)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8116fc16)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff81172108)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8118423c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff811aee87)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811b0f0e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812e65eb)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff812ed068)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In mm/filemap.c (ffffffff812ee8e4)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In mm/page-writeback.c (ffffffff81300854)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f3e9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff813229ee)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff81330abc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134a928)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mmap.c (ffffffff81352a2b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8135c1a7)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff81372e7e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff81377989)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8137b96e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff813b08c9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff813ba567)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff813dcd59)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8144799e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff8149000c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8149ab6a)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8153fffd)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff81544a25)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff815796bb)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81588b58)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff815a3c81)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff815a4b23)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8163e019)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff8168c845)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff81692b47)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff816b8276)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff816d9bc6)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_hash_wake
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ade76)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817aeca0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff817b5239)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff817b61c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff817dcd2c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff818338aa)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c4890)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd7f1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff818f912e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff819011cc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81932c4c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/base/cacheinfo.c (ffffffff819888c0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7935)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d90b8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff819e35dc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a034d1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81a54092)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81a6009a)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81a9875b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81aa7f1b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af9266)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b20479)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b54053)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81b61e29)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9b73e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81bb9702)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81be5eea)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81c0d93b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/sched/sch_generic.c (ffffffff81c94f95)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81cbb696)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e0ee17)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81e23267)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023a30)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103b2b5)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8105e155)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81067ac0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076d95)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083e50)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8a11)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7610)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810ef00c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff810f3115)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff81196f81)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff811a6054)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/irq/matrix.c (ffffffff811a8818)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811bf4cc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef647)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811f1b4e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff813500c8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff813573e8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In mm/filemap.c (ffffffff81358f14)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8136b151)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff8137e700)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff813a792d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c3518)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mmap.c (ffffffff813cca86)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff813d5ea8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff813f05fe)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff813f5201)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff813f92e3)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/migrate.c (ffffffff8143143d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff8143cb91)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memory-failure.c (ffffffff814623a9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff814d64fe)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81523b62)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8152f0a7)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff815deafd)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8161ed4b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8162f048)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8164d941)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8164ead3)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff816f5c43)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/elevator.c (ffffffff81730d3e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister_queue
```
```
In block/blk-mq-tag.c (ffffffff8174b015)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff81750fca)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff8177872f)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff817a5bf6)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_hash_wake
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c7486)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c820c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff818cf559)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff818d0721)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff818ff09c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff81967536)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a150b0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30cd1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a51fbe)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81a5b0cc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81a9184c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/base/cacheinfo.c (ffffffff81af76a0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52775)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b540f8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81b5f236)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81ff1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81bdd88d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c1b617)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81c2ef2b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c87394)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb2799)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ceccf0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81cfc01d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81d5ea32)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff81d9210a)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81dc10ab)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/sched/sch_generic.c (ffffffff81e50a65)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/ethtool/ioctl.c (ffffffff81e79c26)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe5357)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff81ff9fea)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023750)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103b385)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8105f805)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81069370)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078f95)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810863f0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bbbe1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff810cad60)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810fafbc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff810ff455)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff811a8a91)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/matrix.c (ffffffff811ba4e8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811d1fac)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff81203df4)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff812062ee)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/bpf/cpumask.c (ffffffff8135d865)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu
```
```
In kernel/events/uprobes.c (ffffffff813812a2)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff81388c6f)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In mm/filemap.c (ffffffff8138a871)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8139d2b3)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813afdea)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff813ca11e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff813daf1b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813f8a1f)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mmap.c (ffffffff8140135b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8140afb8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff8142418e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff814283dc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8142c077)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/migrate.c (ffffffff81466dbd)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814721e7)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memory-failure.c (ffffffff81496e54)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff8150ca6e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/quota/dquot.c (ffffffff8155b398)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8161655d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8165710b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff816672ab)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff816860f1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81687333)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8172ffaa)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_check_last_writer
```
```
In block/elevator.c (ffffffff8176cf9e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister_queue
```
```
In block/blk-mq-tag.c (ffffffff81787727)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff8178d59a)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff817b830f)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff817e6e96)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_wake
```
```
In lib/group_cpus.c (ffffffff818e6a8f)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190a4e8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b9fe)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff819124f9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff819136b1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff8194262c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff819adb06)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5e170)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a4e1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a9c2ce)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81aa5718)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81add0bc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af42)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/base/cacheinfo.c (ffffffff81b458e0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba5c35)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7648)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81bb27af)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd5d01)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81c344a1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c8253c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81c9618b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d19db9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55a10)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81d63c3d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7c5e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81dc96e9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81e30cfb)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/sched/sch_generic.c (ffffffff81eac275)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/ethtool/ioctl.c (ffffffff81ed5f26)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82061667)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff82076711)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029880)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d7ee)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81041845)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81066965)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810707e0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080665)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d2d0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/mm/pgtable.c (ffffffff810d32b0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8110445c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff81108b05)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_clear_sched
```
```
In kernel/irq/manage.c (ffffffff811b85f1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/matrix.c (ffffffff811ca3a8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811e6c2c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a3b4)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8121d4fe)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/bpf/cpumask.c (ffffffff81386605)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu
```
```
In kernel/events/uprobes.c (ffffffff813aa652)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In kernel/watch_queue.c (ffffffff813b26cf)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In mm/filemap.c (ffffffff813b4391)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff813c3cf5)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/swap.c (ffffffff813cb7af)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813d92d7)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff813f4aae)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/compaction.c (ffffffff814050a9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff814245dc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mmap.c (ffffffff8142d9a9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff814377b0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In mm/page_alloc.c (ffffffff81450fb5)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
```
```
In mm/madvise.c (ffffffff81461cc4)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff814657d4)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/migrate.c (ffffffff8149601d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a2377)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memory-failure.c (ffffffff814c6c56)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
```
```
In fs/buffer.c (ffffffff815416de)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/quota/dquot.c (ffffffff8159195c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff8164f37d)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81690d61)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff816a15fb)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff816c2501)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff816c3816)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff81770938)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_check_last_writer
```
```
In block/elevator.c (ffffffff817af1ce)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister_queue
```
```
In block/blk-mq-tag.c (ffffffff817c9df7)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (ffffffff817cfdfa)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-zoned.c (ffffffff817fce02)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
```
```
In io_uring/io-wq.c (ffffffff8182ce36)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_wake
```
```
In lib/group_cpus.c (ffffffff8192daaf)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951ff5)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8195371e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8195a359)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8195b5f1)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/pci/pcie/dpc.c (ffffffff8198b8bc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/acpi/ec.c (ffffffff819f7f86)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab0860)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acd031)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81aeed9e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81af8168)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81b304bc)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5a995)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_read_and_clear_dirty
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b64540)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_read_and_clear_dirty
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70a72)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/base/cacheinfo.c (ffffffff81b9dd90)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9eb5)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb8f8)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/nvdimm/label.c (ffffffff81c06c9f)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a955)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/phy/phy.c (ffffffff81ce8b0f)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d36e7c)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81d4ac6b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcfad9)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c920)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81e1aba0)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5f98e)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81e82199)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff81eef28b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
```
```
In net/sched/sch_generic.c (ffffffff81f6ed05)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/ethtool/ioctl.c (ffffffff81f99a89)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82134377)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/mptcp/protocol.c (ffffffff8214d310)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
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
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:__mptcp_sync_state
```
```
In net/handshake/tlshd.c (ffffffff8216a58b)
Location: include/asm-generic/bitops/instrumented-atomic.h:82
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int test_and_clear_bit(unsigned int nr, volatile long unsigned int *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff800010088068)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
```
```
In arch/arm64/kernel/signal.c (ffff800010093410)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/mm/context.c (ffff8000100afb1c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In virt/kvm/arm/arm.c (ffff8000100c748c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
```
```
In kernel/cpu.c (ffff8000100fa244)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In kernel/softirq.c (ffff8000100ff3b0)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In kernel/irq/manage.c (ffff8000101798d0)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/irq/affinity.c (ffff800010187ee4)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3a6c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffff8000101b5e60)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffff8000102a810c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffff8000102afbc8)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffff8000102be90c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffff8000102c1058)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffff8000102cad30)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffff8000102ddb0c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffff8000102fd984)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffff800010304410)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffff800010308fa4)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffff800010da01c8)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffff80001031f3c4)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffff800010321948)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffff800010352fe8)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffff800010356270)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffff80001036fdfc)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/select.c (ffff8000103a2378)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/buffer.c (ffff8000103dbf48)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/eventpoll.c (ffff8000103f2db4)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
```
```
In fs/aio.c (ffff8000103fce00)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffff800010405b9c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
```
In fs/quota/dquot.c (ffff800010431558)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffff80001043aa3c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffff8000104cc8e0)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffff8000104d2578)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffff80001050777c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffff800010514f80)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffff80001052d448)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffff80001052e654)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae23c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffff8000105f4324)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffff80001062019c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9e10)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffff8000106d8234)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In drivers/pwm/sysfs.c (ffff8000106d9a30)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffff8000107715fc)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082a200)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083e240)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffff800010859468)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffff800010864a44)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aa880)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffff8000108e0f68)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffff8000108f43e8)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffff800010951ce0)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In drivers/nvdimm/label.c (ffff80001095e920)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffff800010979810)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffff8000109dbe2c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e34a0)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
```
```
In drivers/usb/core/hub.c (ffff800010a19b34)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffff800010a2c3cc)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7e460)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa348c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adfbfc)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffff800010aef50c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
Direct callers:
  - drivers/md/md.c:md_start_sync
```
```
In drivers/md/md-bitmap.c (ffff800010afad2c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffff800010b49004)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/perf/arm-cci.c (ffff800010b90d10)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_free_irq
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96b3c)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a804)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c4f0)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
```
```
In net/socket.c (ffff800010ba23ac)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffff800010bcd9a4)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffff800010c398c0)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76774)
Location: include/asm-generic/bitops/atomic.h:45
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
**Symbols:**

```
ffff800010ae7ba0-ffff800010ae7c14: test_and_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c0000000001230a0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_check_resend
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012a178)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
```
In kernel/cpu.c (c0000000001413f0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In kernel/softirq.c (c000000000146750)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In kernel/irq/manage.c (c0000000001d4060)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/irq/affinity.c (c0000000001e1c70)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/livepatch/transition.c (c0000000001f3a60)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (c000000000219188)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (c00000000021b834)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (c00000000035b2f0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (c000000000361648)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (c000000000377624)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (c00000000037c0c4)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (c000000000387ac8)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (c00000000039d270)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/mlock.c (c0000000003c8e98)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (c0000000003d1240)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (c0000000003d837c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (c000000000eece00)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (c0000000003f473c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (c0000000003f70a4)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (c000000000439b88)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (c00000000043c880)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (c000000000460ba0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (c0000000004e3c98)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (c0000000005458ec)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (c00000000054e528)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (c000000000605fd0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (c00000000060bd30)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (c00000000064cd80)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (c00000000065d594)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (c00000000067956c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (c00000000067abd0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (c00000000072cf34)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (c00000000078bb44)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (c0000000007bf848)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (c000000000847c28)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (c00000000084f3b0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In drivers/pwm/sysfs.c (c000000000851124)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6444)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/tty/tty_ioctl.c (c0000000008f8a1c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (c000000000903b80)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (c0000000009417b8)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (c000000000974d10)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (c00000000098e3b0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (c0000000009fe2d8)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In drivers/nvdimm/label.c (c000000000a10b5c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (c000000000a34210)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (c000000000a9de5c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In drivers/usb/core/hub.c (c000000000ad30cc)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (c000000000ae94cc)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (c000000000b56bf0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (c000000000b82110)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc7ca0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (c000000000bdadcc)
Location: arch/powerpc/include/asm/bitops.h:154
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
In drivers/md/md-bitmap.c (c000000000be8da0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (c000000000c3cbd8)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (c000000000c75ef0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (c000000000ca598c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (c000000000d326b0)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb4c8c)
Location: arch/powerpc/include/asm/bitops.h:154
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/riscv/kernel/signal.c (ffffffe0000b6a30)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
```
```
In kernel/cpu.c (ffffffe0000c43bc)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In kernel/softirq.c (ffffffe0000c7258)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In kernel/irq/manage.c (ffffffe0001144d4)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/irq/affinity.c (ffffffe00011d81a)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-sched.c (ffffffe00013bfb6)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In mm/filemap.c (ffffffe0001d45ce)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffe0001e0fec)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffffffe0001e3528)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffe0001e9ce8)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffe0001f5e54)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffe00020c184)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffe000210bb0)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffe000213d0c)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffe000047502)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffe000220c3a)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffe000222b22)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffe00023e440)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/page_idle.c (ffffffe000250776)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/select.c (ffffffe00026a92c)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/buffer.c (ffffffe000294414)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/eventpoll.c (ffffffe0002a4bcc)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (ffffffe0002ac580)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffe0002b0f5e)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
```
```
In fs/quota/dquot.c (ffffffe0002cce42)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffe0002d22aa)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffe0003452b4)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffe000349612)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffe000373632)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffe00037e556)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffe00038f0f4)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffe00038fcf6)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f64c8)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffe0004323de)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffe00045290c)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004ad14c)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffe0004b171c)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffe0004b24d6)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00052026e)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/tty/tty_ioctl.c (ffffffe0005340ba)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffe00053b084)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffe00055f4a2)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffe00057679a)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffe0005859ce)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffe0005c119c)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffe0005cc7fc)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0eea)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffffffe000626368)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffe00063e678)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffe00064d510)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffe00069512e)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006af866)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7694)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffe0006e3a24)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec640)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffe00071c336)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffe0007399a2)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffe0007555f0)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffe0007aacae)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a5c50)
Location: arch/riscv/include/asm/bitops.h:84
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
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
In arch/x86/events/amd/ibs.c (ffffffff8100aae5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017255)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025815)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103d215)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81043b7b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d415)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058fa2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e90)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81086a71)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8109dea4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/softirq.c (ffffffff810a1416)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811100d4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8111a2f3)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8111b1e2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81126c89)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811406c5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81141db2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812148a8)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81218bd1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff81227b0b)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812324ff)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff81240f6e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff8125efb2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8126598a)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8126bade)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81a6bfbf)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8127d9fe)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127f55b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812aad68)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c41a3)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81360ec3)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff81368f04)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813ea7f4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813eea91)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8141c5c8)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff814288e3)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8143cdd1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8143da05)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814ae4df)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814ecbec)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff81510d3f)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81567a5c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8156ba69)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8156ca42)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815d63e2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626982)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639bd7)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8165036e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff81656ceb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8167fbbb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816bc896)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff816cc5bc)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff81705651)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817118d0)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729cf1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/nvme/host/core.c (ffffffff81748631)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_scan_work
```
```
In drivers/nvme/host/pci.c (ffffffff8174ce15)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
```
```
In drivers/net/tun.c (ffffffff81785986)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817a2711)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817b2e7b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f7e8b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818144dd)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834b03)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff81840fcc)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff81887932)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818ac998)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff818cc8db)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff8192df45)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a43a7e)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016685)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/process.c (ffffffff8102c8c5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810331ab)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103ca75)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810491a2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/mm/pgtable.c (ffffffff81075701)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8108c8c4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/softirq.c (ffffffff8108feca)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81100e04)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff8110b363)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8110c252)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff811196e9)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff81133445)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81135112)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81207618)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff8120bde1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff8121ac5b)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812255ab)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff81233f6e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff812513e2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff81257daa)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8125db7e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81a28506)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8126f896)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127137b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff8129c69f)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812b51e3)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81351b63)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8135a04c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813db274)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813df511)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8140d048)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81419363)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff8142d841)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8142e475)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff8149eeff)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814dd13c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8150105f)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815588ac)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/acpi/ec.c (ffffffff815bffab)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/acpi/nfit/core.c (ffffffff815f3ecd)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_query_poison
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161b002)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/tty/tty_ioctl.c (ffffffff816307be)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8163707b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/base/cacheinfo.c (ffffffff816a78ec)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff816d90d1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816e5350)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb902)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81703111)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/nvme/host/core.c (ffffffff8172a251)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_scan_work
```
```
In drivers/nvme/host/pci.c (ffffffff8172ccb5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_suspend_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
```
```
In drivers/net/tun.c (ffffffff817652d6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81794551)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817a48ab)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bd02b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dbc0d)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc193)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff8180862c)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff8183f2b2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818668e8)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8188696b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff818e7a45)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a0066e)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017215)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025675)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103d055)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff810439bb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d255)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810593d2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077e40)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81086a21)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff8109de54)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/softirq.c (ffffffff810a13c6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110dfc4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff811181e3)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff811190d2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff81124b79)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8113e575)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113fc62)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff81212648)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff81216971)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff812258ab)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8123029f)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8123ed0e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff8125cd52)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff8126372a)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff8126987e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81ad83cf)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8127b79e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127d2fb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812a8b78)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c1fb3)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff8135e993)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff813669d4)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813e7b74)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff813ebe11)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff81418768)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff81424a83)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff81438f71)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81439ba5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814aa57f)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff814e8c7c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff8150cdcf)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815665cc)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff8156a9a9)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8156b982)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815d87db)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654952)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81667d27)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff8167e72e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff816850ab)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816adf9b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff816ead66)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff816fab2c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff81744421)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817506a0)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768ac1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffffffff817b5d36)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817df1b1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff817ef91b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183495b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185365d)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81884133)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff818905fc)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818d8dd2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff818fd998)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8191d8db)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff8197f0d5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aaf92e)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017455)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810260f5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103e0e5)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/step.c (ffffffff81044dbb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e665)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a872)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079f2e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In arch/x86/mm/pgtable.c (ffffffff81088b51)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In kernel/cpu.c (ffffffff810a5d44)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/softirq.c (ffffffff810a9346)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81119504)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_check_affinity
```
```
In kernel/irq/affinity.c (ffffffff81123873)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81124782)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign_system
```
```
In kernel/livepatch/transition.c (ffffffff8113098c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/time/tick-broadcast.c (ffffffff8114b085)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8114c792)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffffffff812215c8)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (ffffffff812259f1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffffffff81234bab)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff8123f6e8)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff8124e43e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffffffff8126c736)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff812730ea)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffffffff81278b0e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffffffff81ae488a)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8128b60f)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8128cec3)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812b8e98)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812d2a53)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (ffffffff81373831)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffffffff8137a030)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffffffff813fd374)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffffffff814017b1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffffffff8142f4e6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8143b913)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffffffff814500e1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81450e15)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffffffff814c2fbf)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffffffff81501c1c)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffffffff815264af)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815804ec)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffffffff81584ea9)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff81585e82)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffffffff815f269b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166ee30)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816822e7)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffffffff81698d8e)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffffffff8169f6ab)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816c83fb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffffffff817055a6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffffffff817153cc)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffffffff8175f871)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8176bb20)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffffffff81784241)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffffffff817d01a6)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817f94a1)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffffffff81809b5b)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184ec79)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186ea2d)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fbf3)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffffffff818ac1ec)
Location: include/asm-generic/bitops-instrumented.h:183
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
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffffffff818f58f2)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (ffffffff8191ea18)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffffffff8193edeb)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffffffff819a1635)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81abbcde)
Location: include/asm-generic/bitops-instrumented.h:183
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
