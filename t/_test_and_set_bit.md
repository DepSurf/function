# Function: <code>_test_and_set_bit</code>

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
  - arch/arm/kernel/perf_event_v7.c:scorpion_pmu_get_event_idx
  - arch/arm/kernel/perf_event_v7.c:krait_pmu_get_event_idx
  - arch/arm/mm/flush.c:__sync_icache_dcache
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_init
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_init
  - kernel/softirq.c:tasklet_kill
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/task_work.c:task_work_add
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/resend.c:check_irq_resend
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:mark_oom_victim
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
  - mm/mlock.c:mlock_vma_page
  - mm/mmap.c:mm_take_all_locks
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memcontrol.c:try_charge
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/fuse/dev.c:fuse_request_end
  - security/keys/key.c:key_revoke
  - security/keys/trusted.c:getoptions
  - security/integrity/ima/ima_fs.c:ima_open_policy
  - block/blk-core.c:blk_queue_flag_test_and_set
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - lib/irq_poll.c:irq_poll_disable
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/pwm/sysfs.c:export_store
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_isr
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:edma_alloc_slot
  - drivers/dma/ti/edma.c:edma_alloc_slot
  - drivers/dma/ti/omap-dma.c:omap_dma_callback
  - drivers/dma/ti/omap-dma.c:omap_dma_callback
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/tty/tty_ioctl.c:tty_throttle
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_poll
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/coupled.c:cpuidle_coupled_poke_others
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_platform_device_create_pdata
  - drivers/perf/arm-cci.c:pmu_get_event_idx
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_alloc_bit
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/netpoll.c:netpoll_poll_dev
  - net/netlink/af_netlink.c:netlink_overrun
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
c0e7e9d8-c0e7ea24: _test_and_set_bit (STB_GLOBAL)
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
