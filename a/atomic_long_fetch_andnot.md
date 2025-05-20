# Function: <code>atomic_long_fetch_andnot</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff8000100880bc)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
```
```
In arch/arm64/kernel/signal.c (ffff800010093418)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In arch/arm64/mm/context.c (ffff8000100afb3c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In virt/kvm/kvm_main.c (ffff8000100bac88)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_clear_dirty_log_protect
```
```
In virt/kvm/arm/arm.c (ffff8000100c7490)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
```
```
In kernel/cpu.c (ffff8000100fa248)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In kernel/softirq.c (ffff8000100ff448)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In kernel/irq/manage.c (ffff8000101798d8)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/irq/affinity.c (ffff800010187f04)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3a8c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffff8000101b5e98)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/events/uprobes.c (ffff8000102a815c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffff8000102afbd4)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
```
```
In mm/page-writeback.c (ffff8000102be914)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
```
```
In mm/swap.c (ffff8000102c129c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffff8000102cae34)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffff8000102ddb60)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mlock.c (ffff8000102fd98c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffff800010304420)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/rmap.c (ffff800010309088)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
```
```
In mm/shuffle.c (ffff800010da01d0)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffff80001031f3cc)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffff80001032195c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffff800010352ff0)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffff800010356284)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffff80001036fe04)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/select.c (ffff8000103a2380)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/buffer.c (ffff8000103dbf4c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/eventpoll.c (ffff8000103f2dbc)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
```
```
In fs/aio.c (ffff8000103fce04)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffff800010405ba4)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
```
In fs/quota/dquot.c (ffff800010431560)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/task_mmu.c (ffff80001043ac04)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/jbd2/transaction.c (ffff8000104cc960)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/revoke.c (ffff8000104d2580)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dir.c (ffff800010507784)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/readdir.c (ffff8000105150a8)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/gc.c (ffff80001052d720)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffff80001052e65c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae248)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In block/blk-mq-tag.c (ffff8000105f4350)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-zoned.c (ffff8000106201cc)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9e1c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
```
In drivers/pwm/core.c (ffff8000106d8274)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In drivers/pwm/sysfs.c (ffff8000106d9a64)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
```
In drivers/acpi/ec.c (ffff800010771608)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082a230)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083e248)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/tty_ioctl.c (ffff8000108594a0)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_unthrottle
```
```
In drivers/tty/sysrq.c (ffff800010864a60)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aa8cc)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
```
In drivers/lightnvm/core.c (ffff8000108e0f84)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
```
```
In drivers/base/cacheinfo.c (ffff8000108f4454)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/bus.c (ffff800010951cec)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In drivers/nvdimm/label.c (ffff80001095e92c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_lib.c (ffff800010979820)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/net/tun.c (ffff8000109dbe38)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e34ac)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
```
```
In drivers/usb/core/hub.c (ffff800010a19b40)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/devio.c (ffff800010a2c40c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7e484)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa34a4)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adfc50)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
```
```
In drivers/md/md.c (ffff800010aef71c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:bb_store
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffff800010afadd8)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
```
In drivers/leds/led-core.c (ffff800010b4904c)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/perf/arm-cci.c (ffff800010b90d28)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_free_irq
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96b78)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a840)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c530)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
```
```
In net/socket.c (ffff800010ba23b8)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - net/socket.c:sock_wake_async
```
```
In net/core/dev.c (ffff800010bcd9e8)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
```
```
In net/sched/sch_generic.c (ffff800010c398ec)
Location: include/asm-generic/atomic-long.h:302
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76780)
Location: include/asm-generic/atomic-long.h:302
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
</details>
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
