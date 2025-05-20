# Function: <code>_test_and_clear_bit</code>

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
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:filemap_check_errors
  - mm/filemap.c:filemap_check_errors
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:shrink_page_list
  - mm/backing-dev.c:clear_wb_congested
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mmap.c:mm_drop_all_locks
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:page_referenced_one
  - mm/shuffle.c:page_alloc_shuffle
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:lookup_swap_cache
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - fs/select.c:poll_select_finish
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/tty/tty_ioctl.c:tty_unthrottle
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/lightnvm/core.c:nvm_remove_tgt_dev
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_get_status
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
  - drivers/perf/arm-cci.c:pmu_free_irq
  - net/socket.c:sock_wake_async
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_hash_del
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
**Symbols:**

```
c0e7e98c-c0e7e9d8: _test_and_clear_bit (STB_GLOBAL)
```
</details>
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
