# Function: <code>test_and_set_bits</code>

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
In arch/powerpc/kernel/pci-common.c (c00000000006cfb0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d942c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_alloc_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_reserve_pe
```
```
In arch/powerpc/xmon/xmon.c (c000000000110744)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/kvm/book3s_hv_ras.c (c000000000120c8c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_realmode_hmi_handler
```
```
In kernel/cpu.c (c00000000013e138)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In kernel/softirq.c (c000000000145b48)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (c000000000163d80)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (c00000000016ec20)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (c000000000ee38f4)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (c0000000001d2790)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (c0000000001d820c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/time/tick-broadcast.c (c00000000021930c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (c00000000021b9a4)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (c0000000002713a0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In kernel/watchdog.c (c000000000283a88)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/uprobes.c (c00000000035b9a8)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (c00000000036e170)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (c0000000003737e8)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (c00000000037cc30)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (c00000000038b108)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (c00000000039d6a4)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In mm/mlock.c (c0000000003c9480)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (c0000000003cb6dc)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In mm/page_alloc.c (c0000000003ee484)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (c000000000eece40)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (c00000000043c690)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (c000000000449a3c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (c000000000456854)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (c000000000460fc8)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (c0000000004c4758)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (c0000000004e3db8)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (c00000000053ab94)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (c0000000005404e0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (c00000000060bd10)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (c000000000646754)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (c000000000679e8c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (c0000000006892bc)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In security/integrity/ima/ima_fs.c (c00000000072c5c0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (c00000000073a0d0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In block/blk-core.c (c00000000077175c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (c00000000078ba54)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (c0000000007ac124)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (c0000000007bf7a4)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (c00000000081cfa0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (c000000000839f24)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (c000000000851724)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6360)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (c0000000008f896c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (c0000000008fb2d4)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In drivers/tty/vt/keyboard.c (c00000000090ee40)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (c000000000913e88)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (c000000000959e84)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (c00000000096bd14)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In drivers/lightnvm/core.c (c0000000009749a8)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (c000000000a062d4)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (c000000000a103c8)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1e584)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (c000000000a227b0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (c000000000a2d530)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (c000000000a303e0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (c000000000a6d0d8)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/spi/spi.c (c000000000a88624)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/tun.c (c000000000aa2970)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (c000000000ad0d88)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (c000000000ad60a0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (c000000000af3148)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b40328)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68fd0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (c000000000b945fc)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b98a68)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c000000000b99d74)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc807c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (c000000000be42a0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c10ecc)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In drivers/of/platform.c (c000000000c47e48)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_device_create_pdata
```
```
In net/core/dev.c (c000000000ca5a00)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (c000000000cd8bf4)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (c000000000cfd50c)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (c000000000d301d0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d48178)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (c000000000d8d410)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c000000000d95b90)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9ccac)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (c000000000e0d880)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6ad80)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (c000000000ecf0d0)
Location: arch/powerpc/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
