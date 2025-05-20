# Function: <code>atomic64_fetch_or</code>

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
In arch/arm64/kernel/debug-monitors.c (ffff800010085f68)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In arch/arm64/kernel/fpsimd.c (ffff8000100884ec)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:do_sve_acc
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a44a0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
```
```
In arch/arm64/mm/flush.c (ffff8000100adcec)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:__sync_icache_dcache
```
```
In virt/kvm/arm/arm.c (ffff8000100c7410)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
```
```
In kernel/cpu.c (ffff8000100fa25c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In kernel/softirq.c (ffff8000100fe988)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffff80001011cbdc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffff800010124fc4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffff800010da2468)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffff8000101788ac)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffff80001017d640)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3ae0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffff8000101b5f74)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffff8000101f9b54)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In kernel/watchdog.c (ffff80001020743c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/uprobes.c (ffff8000102a8400)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/oom_kill.c (ffff8000102b7174)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bc070)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffff8000102c2b28)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffff8000102cd6cc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffff8000102dda60)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/backing-dev.c:set_wb_congested
```
```
In mm/mlock.c (ffff8000102fde6c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffff8000102ffee4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In mm/page_alloc.c (ffff80001031aca4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffff800010da0218)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffff800010356210)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035ef90)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffff8000103688b0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffff80001036f448)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffff8000103c6f48)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In fs/buffer.c (ffff8000103daf18)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffff80001042a2dc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In fs/quota/dquot.c (ffff800010432938)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/jbd2/revoke.c (ffff8000104d25c4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffff80001050289c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffff80001052df9c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffff80001053acd4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffff8000105adb58)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b6128)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In block/blk-core.c (ffff8000105e0e4c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffff8000105f4264)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffff80001060eb20)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffff800010620100)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffff800010667be0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473d1c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/gpio/gpiolib.c (ffff8000106c18f0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffff8000106d9c78)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/acpi/tables.c (ffff80001147bfc8)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffff8000107710dc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/amba-pl08x.c (ffff800010802184)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
```
```
In drivers/dma/bcm2835-dma.c (ffff80001080538c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/mv_xor.c (ffff8000108065c4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808890)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler
```
```
In drivers/dma/mxs-dma.c (ffff80001080a1cc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d034)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082aae0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/xen/events/events_2l.c (ffff800010832e24)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffff8000108337b4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
```
```
In drivers/tty/tty_ioctl.c (ffff800010859688)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffff80001085bed8)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffff80001086e8cc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffff80001087330c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffff8000108b90e4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffff8000108c50d4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1208)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d4034)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_bitmap_alloc
```
```
In drivers/lightnvm/core.c (ffff8000108e0c28)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffff800010957f1c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffff80001095e4a4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffff8000109676e4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a090)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffff8000109739f0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffff800010977890)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffff8000109a6bc4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/spi/spi.c (ffff8000109c7b24)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/tun.c (ffff8000109dcf68)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fd884)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/usb/core/hub.c (ffff800010a180ac)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffff800010a1ccc0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffff800010a35cf4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6cfe0)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c88c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab1738)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab48d4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffff800010ab6d74)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adff28)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffff800010af8a4c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1f58c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In drivers/of/platform.c (ffff800010b6da48)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_platform_device_create_pdata
```
```
In drivers/perf/arm-cci.c (ffff800010b9115c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In drivers/perf/arm-ccn.c (ffff800010b92e14)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_alloc_bit
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99acc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
```
```
In net/core/dev.c (ffff800010bcda10)
Location: include/asm-generic/atomic-instrumented.h:1333
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
In net/core/link_watch.c (ffff800010bf3954)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffff800010c11054)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffff800010c37ffc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4c0dc)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffff800010c82a70)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffff800010c88800)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e2a4)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffff800010cea05c)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39d58)
Location: include/asm-generic/atomic-instrumented.h:1333
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
