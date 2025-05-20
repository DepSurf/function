# Function: <code>test_and_clear_bits</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c0000000001230a0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_check_resend
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012a190)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
```
In kernel/cpu.c (c000000000141408)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (c000000000146750)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In kernel/irq/manage.c (c0000000001d4060)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/irq/affinity.c (c0000000001e1c80)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/livepatch/transition.c (c0000000001f3a60)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
```
In kernel/time/tick-broadcast.c (c000000000219190)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (c00000000021b834)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (c00000000035b2f0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/filemap.c (c000000000361648)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (c000000000377624)
Location: arch/powerpc/include/asm/bitops.h:136
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
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (c000000000387ac8)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (c00000000039d274)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/mlock.c (c0000000003c8e98)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (c0000000003d1240)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (c0000000003d837c)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (c000000000eece00)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (c0000000003f473c)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (c0000000003f70a4)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (c000000000439b88)
Location: arch/powerpc/include/asm/bitops.h:136
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
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (c000000000460ba0)
Location: arch/powerpc/include/asm/bitops.h:136
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
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/quota/dquot.c (c0000000005458ec)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (c00000000054e528)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (c000000000605fd0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (c00000000060bd30)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (c00000000064cd80)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (c00000000065d594)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (c00000000067956c)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (c00000000067abd0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (c00000000072cf34)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (c00000000078bb44)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (c0000000007bf848)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (c000000000847c28)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (c00000000084f3b0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In drivers/pwm/sysfs.c (c000000000851124)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6444)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/tty/tty_ioctl.c (c0000000008f8a1c)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (c000000000903b98)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (c0000000009417b8)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (c000000000974d24)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (c00000000098e3cc)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (c0000000009fe2d8)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In drivers/nvdimm/label.c (c000000000a10b5c)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (c000000000a34214)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (c000000000a9de5c)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In drivers/usb/core/hub.c (c000000000ad30cc)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (c000000000ae94d8)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (c000000000b56c08)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (c000000000b82110)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc7ca0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (c000000000bdadcc)
Location: arch/powerpc/include/asm/bitops.h:136
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
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (c000000000c3cbd8)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In net/socket.c (c000000000c75ef0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (c000000000ca598c)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (c000000000d326b0)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb4c98)
Location: arch/powerpc/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
</details>
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
