# Function: <code>fls</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f32b)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810405f1)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041f3b)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b2196)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff810ff7b6)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff8114330b)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81185ab7)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In mm/page-writeback.c (ffffffff81198d92)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/vmstat.c (ffffffff811ad716)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff811b004d)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff811b4ab7)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff811cd20c)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff811ed58d)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8123a5ec)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81244cc0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
```
```
In fs/proc/array.c (ffffffff8127fd3e)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/ext4/inode.c (ffffffff81297696)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff812cd7da)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/fuse/dir.c (ffffffff81313356)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81317015)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
```
```
In fs/fuse/inode.c (ffffffff8131bcfe)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff813c4950)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In block/blk-integrity.c (ffffffff813e7b5b)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/flex_proportions.c (ffffffff813e9781)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu_max
```
```
In lib/idr.c (ffffffff813e9bdc)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_destroy
```
```
In lib/bitmap.c (ffffffff813f9904)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff813fddc6)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In lib/reciprocal_div.c (ffffffff81400d20)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff814bdb18)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff814c6466)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8150ddfc)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/char/random.c (ffffffff81512825)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff81536ef3)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153d477)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/platform.c (ffffffff8154d7bc)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/base/platform.c:dma_get_required_mask
  - drivers/base/platform.c:dma_get_required_mask
```
```
In drivers/block/loop.c (ffffffff81fad7b8)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588675)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ae500)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_sg_alloc
  - drivers/scsi/scsi_lib.c:scsi_sg_free
```
```
In drivers/scsi/sd.c (ffffffff815bdc63)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf7e8)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_complete
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff815c7186)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-transport.c (ffffffff815dacb0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff815e4d16)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff81610413)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff81616623)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8164c13b)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81653e2b)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff816ac241)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff816c0016)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff816e3726)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/clk/clk-mux.c (ffffffff816ea307)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8177994c)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:437
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f152)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040440)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041f0f)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b4c66)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff81106ba5)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff8114d53f)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff8116006e)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81197b34)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In mm/page-writeback.c (ffffffff811addd7)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff811c68cf)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff811cabf7)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff811cdb7a)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff811ebcca)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff8120cf3c)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8126234c)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8126d880)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/proc/array.c (ffffffff812acd92)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/ext4/inode.c (ffffffff812c4cd7)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8130409e)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff813478d3)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8134ecaf)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff813507ee)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81408af9)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In block/blk-integrity.c (ffffffff8142ddeb)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/flex_proportions.c (ffffffff8142fed6)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In lib/idr.c (ffffffff814300f3)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_destroy
```
```
In lib/bitmap.c (ffffffff81440924)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81445436)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In lib/reciprocal_div.c (ffffffff814484c3)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In lib/sg_pool.c (ffffffff81461ddb)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8150d7c8)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81517283)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81560251)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/char/random.c (ffffffff81566b32)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158b1e3)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815920e9)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/platform.c (ffffffff8159f5cc)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/base/platform.c:dma_get_required_mask
  - drivers/base/platform.c:dma_get_required_mask
```
```
In drivers/base/regmap/regmap.c (ffffffff815b9099)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff81fda2f3)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815dd6f8)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff815f076f)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81616afb)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_dif.c (ffffffff816181f2)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff816281a4)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81634890)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81642746)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff8166ffef)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff816766fb)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816acab7)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b48cb)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff8170c768)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81723485)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81747a22)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/clk/clk-mux.c (ffffffff8174ea76)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6b1c)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: arch/x86/include/asm/bitops.h:437
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:437
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103eb2f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103fe80)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104195b)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810bc2aa)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff8110e336)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff8115747f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff8116aace)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811a7510)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811be4b9)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff811d6a60)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff811dad17)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff811ddcca)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff811fb376)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff8121ef9c)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8127584f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81280ad0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/proc/array.c (ffffffff812c2684)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/ext4/inode.c (ffffffff812da394)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8131a05e)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8135d1f8)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff813645bd)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8136614e)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81423657)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-integrity.c (ffffffff81447bab)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/flex_proportions.c (ffffffff8144c106)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In lib/idr.c (ffffffff8144c323)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_destroy
```
```
In lib/bitmap.c (ffffffff8145da24)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81463c26)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/reciprocal_div.c (ffffffff81466eb3)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/sg_pool.c (ffffffff8148091b)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff815372e6)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff815398f8)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81543652)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8158c9c1)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/char/random.c (ffffffff81593292)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b8933)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bf9a9)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/platform.c (ffffffff815cdbcc)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/base/platform.c:dma_get_required_mask
  - drivers/base/platform.c:dma_get_required_mask
```
```
In drivers/base/regmap/regmap.c (ffffffff815e833f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff82017dd1)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a388)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161d6a3)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff816465ad)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_dif.c (ffffffff81647d92)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648bf7)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_unlock_zone
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_write_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81658e14)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff816659e0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81673826)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff8169dccd)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff816a4219)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/xhci.c (ffffffff816dabc7)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e2a7b)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff8173e7a8)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff817562f5)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b332)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8181720c)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/ipv4/udp.c (ffffffff820297c0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:450
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103cb02)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ddf1)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fb7d)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b6d0a)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff8110fab6)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff820c961d)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_init_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff8116da8d)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8119cac0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff8119e6c4)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811aecb2)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811c785b)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff811df8c0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff811e4712)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff811e79de)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff812060b6)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff8122b64f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81282d8b)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8128e390)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/proc/array.c (ffffffff812cf914)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/ext4/inode.c (ffffffff812fe23f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81311413)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff81371c7d)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81378d98)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8137a80e)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81431a4b)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/blk-integrity.c (ffffffff814560e6)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/sed-opal.c (ffffffff8145de49)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/bitmap.c (ffffffff8146307a)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81468cd6)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/reciprocal_div.c (ffffffff8146c373)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/sg_pool.c (ffffffff81489adb)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff8154a616)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff8154d0b8)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815574d6)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff815a0a95)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/char/random.c (ffffffff815a7092)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff815ceb73)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d554a)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/platform.c (ffffffff815e25fc)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/base/platform.c:dma_get_required_mask
  - drivers/base/platform.c:dma_get_required_mask
```
```
In drivers/base/regmap/regmap.c (ffffffff815fcab8)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff820f9bb7)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161e493)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff81631b2f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8165b123)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c8d0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d526)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_write_unlock_zone
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8166c31d)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff8167a180)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81687f66)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff816b31c4)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff816b9405)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/xhci.c (ffffffff816f1716)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f6b6b)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff817585e3)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81774325)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81799d40)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fc6f)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8210cd5a)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
```
```
In lib/flex_proportions.c (ffffffff818ec8b6)
Location: arch/x86/include/asm/bitops.h:450
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f6f6)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040951)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042f09)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3d82)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810be07a)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810d72f6)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff8111ad96)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff81167ad3)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff8117ab4d)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cd54)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811ac543)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811ae105)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811c2842)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811dc69b)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff811f56e0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff811f99bc)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff811fdc1e)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff8121edd6)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff81246d5c)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a58db)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812b0f9d)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/proc/array.c (ffffffff812f4072)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/ext4/inode.c (ffffffff81322a2f)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81332fd1)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8139697d)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8139dc38)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8139f6ae)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff8145d3c2)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/blk-integrity.c (ffffffff81481d46)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/sed-opal.c (ffffffff81489c29)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/bitmap.c (ffffffff8148ef90)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81494f86)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/reciprocal_div.c (ffffffff81498673)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/sg_pool.c (ffffffff814c5c2b)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff815adb9e)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff815b0628)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815bb732)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff816061c5)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/char/random.c (ffffffff8160d992)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816358e3)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c2fa)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/platform.c (ffffffff8164979c)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/base/platform.c:dma_get_required_mask
  - drivers/base/platform.c:dma_get_required_mask
```
```
In drivers/base/regmap/regmap.c (ffffffff81664c58)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff82703386)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81686cd3)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169a48f)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff816c47b5)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff816c5f30)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6b7c)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_write_unlock_zone
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff816d5970)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff816e37e0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff816f1846)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff8171e851)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff81724d18)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/xhci.c (ffffffff8175d996)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817635db)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff817ca853)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff817ea6c5)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818100e0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf00f)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8271706e)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81972886)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040bdc)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104222d)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044d70)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045f23)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d650)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In kernel/sched/core.c (ffffffff810baf8f)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810c5da8)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810e1b95)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff81127b15)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811767d6)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff81189bb7)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bdba)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811c3b45)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811c5deb)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_get_next_key
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/lpm_trie.c:trie_lookup_elem
```
```
In kernel/bpf/sockmap.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811e2b93)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811fe9a1)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff81216935)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff8121bbc0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff8121ef4b)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff812416a6)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff8126812f)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cc657)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812d8e22)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/proc/array.c (ffffffff81321482)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/ext4/inode.c (ffffffff8135040a)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81364387)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff813c5504)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff813cd008)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff813cea3e)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81490e64)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/deadline-iosched.c (ffffffff814ada2e)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814b6996)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/blk-zoned.c (ffffffff814b8003)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff814c3ba6)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff814ca2b0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In lib/reciprocal_div.c (ffffffff814cd850)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - lib/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In lib/sg_pool.c (ffffffff814f6b56)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff815e5dee)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff815e8a85)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/balloon.c (ffffffff815f3c88)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81640187)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81647497)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff81670f93)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677848)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/platform.c (ffffffff81684d5c)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/base/platform.c:dma_get_required_mask
  - drivers/base/platform.c:dma_get_required_mask
```
```
In drivers/base/regmap/regmap.c (ffffffff816a0586)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff8272d107)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c2e1c)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d675d)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81700cd4)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff817024d3)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff81702fde)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8171169d)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81720075)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff8172e265)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff8175d28d)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817639ee)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/xhci.c (ffffffff8179e375)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a3825)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff81813760)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81833620)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81859f99)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914bd0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In net/ipv4/udp.c (ffffffff827414b0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
```
```
In lib/flex_proportions.c (ffffffff819cecb6)
Location: arch/x86/include/asm/bitops.h:454
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810421fb)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104384d)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046780)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047947)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81048515)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810632e0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c44bf)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810ce748)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810ec2e5)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/dma/mapping.c (ffffffff81118153)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff811331f5)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff8118441f)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff81197467)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811997d8)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811d56e5)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811d7258)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811f3003)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8120f1a6)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff8122985c)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff8122eba0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff81231f64)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff81255da6)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff8127dc4b)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e1887)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812ee2f2)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/proc/array.c (ffffffff81338592)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In fs/ext4/inode.c (ffffffff8136876d)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8137c62a)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff813de6a4)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff813e6390)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff813e7eb8)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814a9cfb)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff814c81a4)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814ca1a6)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814cafe3)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In block/blk-zoned.c (ffffffff814cbaf3)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff814d8276)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff814defd0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/reciprocal_div.c (ffffffff814e1e60)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/reciprocal_div.c:reciprocal_value_adv
  - lib/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/sg_pool.c (ffffffff8150af96)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815609f3)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff8160017e)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff816028d5)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff8160fe14)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8165e3b7)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81665937)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168eed7)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/iommu/intel-pasid.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696928)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816c0d33)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff828e5a87)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e421f)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f853c)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81723da8)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81725a24)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/scsi/sg.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81733b50)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81742965)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81750a45)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff81781805)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81788042)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/host/xhci.c (ffffffff817c4565)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817c9b45)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183f760)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff8185f5b0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81879239)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81934738)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943382)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/ipv4/udp.c (ffffffff828fb716)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a08176)
Location: arch/x86/include/asm/bitops.h:451
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044777)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81045dad)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810491b3)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a6b0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b2b5)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104b83e)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066989)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810ca21d)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810d6af5)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810eff9b)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff811224ce)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff8113e035)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811911a1)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff811a56a6)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7407)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811e9f43)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811ebc24)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8120ad1f)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8121ecd2)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff81239514)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff8123e37e)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff81242414)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff81268efb)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff81299a81)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fffc1)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130fac6)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In fs/proc/array.c (ffffffff81360c52)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff813918b5)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a2ed0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff81409bc3)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814122e9)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81413f58)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814d7ca6)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff814f6a27)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814f8a76)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814f9905)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In block/blk-zoned.c (ffffffff814fa793)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff81503f3a)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff8150ae90)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff81510840)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In lib/sg_pool.c (ffffffff815396a6)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81590dea)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff81632a3b)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff816350f5)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff81643c34)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/max310x.c (ffffffff81692f97)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff8169bcf7)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c63b7)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf238)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816fbb33)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff829001c6)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171d8b7)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff81731bfd)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8175efc8)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81761023)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/ata/libata-core.c (ffffffff81771ec2)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff8177e615)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff8178c725)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff817bfe20)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817c5b61)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81803d35)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81809f65)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff81882512)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff818a3178)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818be415)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81998278)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f055)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7926)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82918115)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a77ac5)
Location: arch/x86/include/asm/bitops.h:325
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044ec7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104650d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049a83)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b055)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bcb2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c1fe)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066ff9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810d347d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810e0619)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810fbdcb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff81149bc5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff8119d1c1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff811b0ed6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2bf7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811f66a3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811f8384)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81217fff)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8122c772)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff812478cc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff8124c7db)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff81250934)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff81277e34)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff812a9941)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813128ff)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81322a46)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/verity/enable.c (ffffffff8134fa19)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81350a97)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff81378eb2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff813aa245)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813bbd30)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff814242fb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8142c029)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8142dff8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814f1022)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff815148d7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81516926)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8151769c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff815186f3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff81521edc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81528cb0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff8152e740)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff8155a4c6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff8165476b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff81656e05)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff816661e4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff816b0f61)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff816b5b37)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff816bea27)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e9327)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3078)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff8171fee3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff82909411)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81741b87)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755d6d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81782fae)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784fe3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/ata/libata-core.c (ffffffff81795e70)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff817a22d5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff817b0335)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8f29)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/urb.c (ffffffff817f07a0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817f67f2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff81834c05)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183aee5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b43b2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff818d5468)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f0f65)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff819899bf)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819ceda8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5af5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de9b6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82921f84)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81aaeeb5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048ed9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a4cd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e206)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f486)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810502cb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050b1e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106dc09)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810dd174)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810e9db9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/debug.c (ffffffff81106518)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff81159b25)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811b3136)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_allocate_pages
```
```
In kernel/trace/tracing_map.c (ffffffff811c9087)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cac32)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81219c93)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff8121c278)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81243b4f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81258606)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_stat_error
  - mm/page-writeback.c:__add_wb_stat
```
```
In mm/vmstat.c (ffffffff81275abe)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff8127aa86)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff8127efa4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff812a8d14)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff812de965)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81348c60)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:__add_wb_stat
```
```
In fs/buffer.c (ffffffff81359230)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_size_bits
```
```
In fs/io_uring.c (ffffffff8137cd57)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff8139627e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff8139749b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff813c1f5f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff813f6cf2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81407232)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8147225e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_fillattr
```
```
In fs/fuse/file.c (ffffffff81475d10)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fuse/inode.c (ffffffff8147dc9f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/blk-core.c (ffffffff81542f9b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/blk-mq.c (ffffffff8154e306)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:queued_to_index
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff815756cb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/blk-integrity.c (ffffffff8157714a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81577e5c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81578950)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/keyslot-manager.c (ffffffff8158112a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff81581d01)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/clz_ctz.c (ffffffff8158c580)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff81592610)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff815e3e86)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In lib/flex_proportions.c (ffffffff815e8b36)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff816f36f5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff81704556)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff81707185)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff81715924)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81764341)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff81768bb5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff817729ac)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a02bc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aae9d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/base/regmap/regmap.c (ffffffff817dbff3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff82d1f631)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ff6a7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff818154a4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff818420e0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sectors_to_logical
  - drivers/scsi/sd.c:bytes_to_logical
  - drivers/scsi/sd.c:logical_to_sectors
```
```
In drivers/scsi/sd_zbc.c (ffffffff81849771)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sectors_to_logical
  - drivers/scsi/sd_zbc.c:logical_to_sectors
```
```
In drivers/ata/libata-core.c (ffffffff81859ffc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81866165)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff81867448)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/spi/spi.c (ffffffff818763b5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6841)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/urb.c (ffffffff818bfd6a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff818c6869)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff81907ad5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190bc45)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff81983bef)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:io_job_start
```
```
In drivers/mmc/core/core.c (ffffffff819a7ca8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6551)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81a616d6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81abaee4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2135)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb6e1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82d2e53c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
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
In arch/x86/events/intel/lbr.c (ffffffff82fb42e0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048374)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049975)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d73e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e767)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f659)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fc82)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f3a9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810d9a14)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810f1221)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/debug.c (ffffffff81104b68)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/printk/printk.c (ffffffff82fdc6c5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/time/timekeeping_debug.c (ffffffff81155b35)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811b0c91)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/tracing_map.c (ffffffff811c6747)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8312)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8121c4b3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff8121f188)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81230416)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8124e1df)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff812657ca)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff8128039e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff81285216)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff81288c14)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff812b3fa8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff812ea77b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81359028)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81369825)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (ffffffff8138b537)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff813a7f9e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff813a8f0b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff813d40af)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff8140952e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8141a482)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8148cb31)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_fillattr
```
```
In fs/fuse/file.c (ffffffff81496bfc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81499019)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/blk-core.c (ffffffff81560315)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff8156cc16)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/mq-deadline.c (ffffffff815926ed)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-integrity.c (ffffffff81593de4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81594adc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81595698)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/keyslot-manager.c (ffffffff8159e147)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff8159ecf1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/clz_ctz.c (ffffffff815a8ff0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff815af1a5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff816083b3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In lib/flex_proportions.c (ffffffff8160dbe6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81710895)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff81721796)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff817245d4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff817322a4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff8177f261)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff81783955)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff8178d9fc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ade44)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8256)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff817f10ca)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff8300d452)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81810947)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff81824694)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8185328b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859ced)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-core.c (ffffffff81c1800f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81874f65)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff81876258)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/spi/spi.c (ffffffff81884be5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5731)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/urb.c (ffffffff818cc8bc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff818d24aa)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff81910275)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819136c5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff81987cff)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:io_job_start
```
```
In drivers/mmc/core/core.c (ffffffff819aaf08)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6441)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ac6284)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdd67)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7686)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8301d0dc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
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
In arch/x86/events/intel/core.c (ffffffff831bcbee)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff831be857)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049b3d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b0f5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f1ce)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050b71)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81051273)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81051832)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106fed9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810db42d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810f3528)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/debug.c (ffffffff81106efe)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/printk/printk.c (ffffffff831e7423)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/time/timekeeping_debug.c (ffffffff81156f65)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811abac5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/tracing_map.c (ffffffff811c7756)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9a83)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8121fed2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff81222c15)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812259f8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81252b13)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8126a2cc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff812854ae)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff812897d8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff8128e2c4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff812b9688)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff812f1f22)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8135fb80)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81370635)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (ffffffff81392723)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff813aeffe)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff813aff7b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff813daeef)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff8140f6ce)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8142256d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff81493b53)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8149bd00)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8149e249)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/blk-core.c (ffffffff815683e9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff81574ab6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/mq-deadline.c (ffffffff8159950f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-integrity.c (ffffffff8159abc4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8159b8af)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff8159c2ec)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/keyslot-manager.c (ffffffff815a4e9f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff815a5b5d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/clz_ctz.c (ffffffff815b3c30)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff815b9f55)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff815eb013)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In lib/flex_proportions.c (ffffffff815f1336)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff816f2155)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff81702ac6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff81705894)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81708822)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/xen/mem-reservation.c (ffffffff81715d74)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81762bb8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff81767245)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff8177135f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81790856)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b3a6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff817d5967)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff832182af)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f50d5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff818078bd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81836cab)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183cb06)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-core.c (ffffffff81c09e07)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81857695)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff81858a78)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/spi/spi.c (ffffffff81867465)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898bd2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/urb.c (ffffffff818aff2e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff818b5a4e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff818f3855)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f6bc5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196c960)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff8198f7a8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819ab2f2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab1498)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8e17)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff832281c1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
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
In arch/x86/events/intel/core.c (ffffffff8329cfa2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8329ecb5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81051411)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810521b7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810572e6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058ea8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81059744)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059dc2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107b92f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810ef9da)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff8110cd88)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/debug.c (ffffffff81124edc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/printk/printk.c (ffffffff832cb589)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/time/timekeeping_debug.c (ffffffff8117bd95)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c9c97)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811d56e5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/tracing_map.c (ffffffff811f2ee0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f556a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8125826a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff8125a9c5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125da01)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8128e3e1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a6f66)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff812c3d86)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff812c9fec)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff812ce1c1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff812fbc28)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff8133aed8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813ae48e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff813bf1ac)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (ffffffff813e09b9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff813febae)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff813ffb6b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff8142c5c9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff814626a7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81475cd6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff814eafbc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814f36e6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff814f60f9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff81502b59)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/blk-core.c (ffffffff815cc9eb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff815d8fd9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/mq-deadline.c (ffffffff8160183f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81602e04)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81603846)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff816045e3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/keyslot-manager.c (ffffffff8160d91f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff8160e63c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/clz_ctz.c (ffffffff81619e20)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff81620905)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff816574a3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In lib/flex_proportions.c (ffffffff8165e4a6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff8176c395)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff8177d756)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff81780de4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81784642)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/xen/mem-reservation.c (ffffffff81792fd4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff817e6cc8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff817ebc19)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff817f6f0f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81818196)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823ed0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff81860ed8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff83301ce3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e175)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff818921ad)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818c4489)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c947c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-core.c (ffffffff818d89d4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff818e60b5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff818e7812)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/spi/spi.c (ffffffff818f6c75)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c5e2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/urb.c (ffffffff819450d6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff8194afad)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81990b05)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81994fe5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81a0629e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a156b5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81a3af1b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a58dd2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b6e454)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76062)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff833125d6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
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
In arch/x86/events/intel/core.c (ffffffff8344ba7d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8344d9e8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105c9df)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105dc07)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8106367c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81064833)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065e0b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81066598)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108aaff)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff81109dba)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff811288d8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/build_utility.c (ffffffff8113b53e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8347ec77)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff81172d60)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/time/timekeeping_debug.c (ffffffff811b14b5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fd878)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8120a845)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/tracing_map.c (ffffffff8122c4b1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122edcd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff812a0f23)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff812a3b2b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7d51)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff812e3261)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In mm/page-writeback.c (ffffffff812ff168)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff81321541)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff813270cc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff8132c279)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff81360c57)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/slub.c (ffffffff813ad7aa)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81432747)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81446022)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/verity/enable.c (ffffffff81472742)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff814738ed)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff814a5e77)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff814e1862)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff814f7fe0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff81579adf)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81583139)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81585db6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff81594113)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In crypto/dh.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In block/blk-core.c (ffffffff816795e9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff81686d63)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/mq-deadline.c (ffffffff816b414d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff816b5d44)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff816b6a46)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff816b7d31)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-crypto.c (ffffffff816c1cf6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff816c21f7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff81e8ed55)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/clz_ctz.c (ffffffff816e72e0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff816eea75)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff8176edcb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In lib/flex_proportions.c (ffffffff81777c0a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff818a12a5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff818b4396)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff818b7584)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb309)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/xen/mem-reservation.c (ffffffff818cb954)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81926607)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff8192caa9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81934a1e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195966c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81963703)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff819a8b45)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff834bad5d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c6645)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff819dc449)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81a10d24)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a169af)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-core.c (ffffffff81a29b79)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81a37545)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff81a38fb2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/spi/spi.c (ffffffff81a47ab5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82c12)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/urb.c (ffffffff81a9d723)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81aa3d57)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81aed225)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af1c95)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81b6df33)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7d06b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81ba7df6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc8bd2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81cfdb3a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81d059d2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff834cc6b1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37d4f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_move
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
In arch/x86/events/intel/core.c (ffffffff83e67e09)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff83e68e22)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a9ff)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106c137)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810726bf)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81073aa3)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81075147)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81075868)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109ebef)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff811314f7)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff81151fa8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_utility.c (ffffffff8116aaf7)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/printk/printk.c (ffffffff83eaad12)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff811aa86e)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff811f2175)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81245048)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8125311e)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/tracing_map.c (ffffffff81277ff1)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127adef)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff812fdce1)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff8130172b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813063d4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/memalloc.c (ffffffff8131c786)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_free
  - kernel/bpf/memalloc.c:bpf_mem_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8134b8d1)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff81369887)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/vmstat.c (ffffffff81395520)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff8139caec)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813a1d97)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/workingset.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/vmalloc.c (ffffffff813dc4e8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/slub.c (ffffffff8142da1a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814c04a5)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814d4fa2)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/verity/enable.c (ffffffff81504432)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81505883)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff8153b4b7)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff8157ab78)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815925d6)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8161f17f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff816290c9)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8162bfe6)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff8163cce3)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In crypto/dh.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In block/blk-core.c (ffffffff81735abd)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff81744a33)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/mq-deadline.c (ffffffff81773c49)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81775804)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81776a06)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81778336)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-crypto.c (ffffffff81782f06)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff817834f7)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff81789fdf)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/clz_ctz.c (ffffffff817d6b20)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff817df695)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In lib/sg_pool.c (ffffffff8189e71b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81925ce4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff819ea905)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff81a00f13)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff81a044b4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09dc9)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/xen/mem-reservation.c (ffffffff81a1cd04)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81a82fe2)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff81a8a469)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81a945aa)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0fd3)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acc7f1)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1bc13)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff83ef873a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d0d3)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b57a0f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81b90f7f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b977d4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-core.c (ffffffff81bac6d6)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81bbc3e5)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff81bbe022)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/spi/spi.c (ffffffff81bcf4e5)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff81c227f3)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81c29ca8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81c79ba5)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c7ee85)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d0a401)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1af9b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81d4a4b9)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d72966)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec279a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecab12)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/udp.c (ffffffff83f0f0de)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_pernet_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81f001af)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In lib/flex_proportions.c (ffffffff820208da)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
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
In arch/x86/events/intel/core.c (ffffffff83687046)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/lbr.c (ffffffff836897c2)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c36f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106dad7)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810742a4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81075953)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810772b7)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff810779d8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109ffc0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/sched/core.c (ffffffff8113f487)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff8116188d)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:__calc_delta
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_utility.c (ffffffff8117b207)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/printk/printk.c (ffffffff836cfcd2)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff811bc7ae)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff81206925)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125c0d8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8126d55f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/tracing_map.c (ffffffff8128fa30)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129290f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8132c8f1)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff81330289)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81335220)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/memalloc.c (ffffffff8134c286)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_free
  - kernel/bpf/memalloc.c:bpf_mem_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8137c921)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff8139ba24)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/vmstat.c (ffffffff813c8140)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff813cfbcc)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813d4c0d)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/workingset.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/vmalloc.c (ffffffff81410e11)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/slub.c (ffffffff8146309a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814f5895)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8150af84)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/verity/enable.c (ffffffff8153bbc3)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff8153cb25)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff815737e7)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff815b0c42)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815c9597)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff816575a4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff816612eb)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81664226)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff816751f3)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In crypto/dh.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In block/blk-core.c (ffffffff81771fed)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/mq-deadline.c (ffffffff817b3f2b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff817b5754)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff817b65d6)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff817b7be0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-crypto.c (ffffffff817c317a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff817c3851)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff817ca8ef)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/clz_ctz.c (ffffffff81815b30)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff8181ee75)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In lib/sg_pool.c (ffffffff818e0ceb)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81969a94)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81a33025)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff81a49c13)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d314)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52c59)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/xen/mem-reservation.c (ffffffff81a65f04)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81ace630)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad5c39)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81adfdca)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0d841)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19383)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6aca9)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff8371e328)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/block/virtio_blk.c (ffffffff81b7efcb)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b9054e)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff81baaf8f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81be69f8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bedd84)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-core.c (ffffffff81c03866)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81c13c55)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff81c15872)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/spi/spi.c (ffffffff81c27155)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff81c89770)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81c909b4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81ce0c95)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce6105)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d7353b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84106)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81db4d19)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81de0706)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f20cfa)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81f295bc)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In net/ipv4/udp.c (ffffffff837356ed)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_pernet_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5fc2f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In lib/flex_proportions.c (ffffffff820a091a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
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
In arch/x86/events/intel/core.c (ffffffff838b6299)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:branch_counter_nr_show
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/lbr.c (ffffffff838b92f2)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810735bf)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074d47)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107cd75)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e842)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a6d90)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:cpu_mark_primary_thread
```
```
In kernel/sched/core.c (ffffffff8114c3e1)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff8116fae0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_utility.c (ffffffff81188bb2)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/printk/printk.c (ffffffff839010e2)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff811cd3e8)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/tree.c (ffffffff811d3dda)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff8121db35)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8127601a)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8128cc27)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace.c (ffffffff8129b756)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_subbuf_size_write
```
```
In kernel/trace/tracing_map.c (ffffffff812aafb9)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adfff)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81350e31)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff813547b6)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/bpf/bloom_filter.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81359880)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/memalloc.c (ffffffff813737ca)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_free_rcu
  - kernel/bpf/memalloc.c:bpf_mem_free
  - kernel/bpf/memalloc.c:bpf_mem_alloc
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff813a5b7e)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c445d)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In mm/vmstat.c (ffffffff813f2a47)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffff813fb19f)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813fec90)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_size_roundup
```
```
In mm/workingset.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143d601)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/slub.c (ffffffff8145f2ea)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
```
```
In fs/pipe.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81529fa2)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/verity/enable.c (ffffffff81570ea3)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81571f85)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff815ac1b7)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff815e9ae9)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff816011ba)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_best_avail
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_best_avail
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_best_avail
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_best_avail
  - fs/ext4/mballoc.c:mb_update_avg_fragment_size
```
```
In fs/ext4/resize.c (ffffffff81615594)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/ext4/resize.c:alloc_flex_gd
  - fs/ext4/resize.c:alloc_flex_gd
  - fs/ext4/resize.c:alloc_flex_gd
```
```
In fs/fuse/dir.c (ffffffff8168f69f)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_fillattr
```
```
In fs/fuse/file.c (ffffffff8169b1ab)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8169e3f3)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff816b15b3)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In crypto/dh.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In block/blk-core.c (ffffffff817b3243)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - block/blk-core.c:blk_check_zone_append
```
```
In block/mq-deadline.c (ffffffff817f7ad4)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff817fa164)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff817fafe6)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff817fc934)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-crypto.c (ffffffff81807e0a)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff818084e1)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff8180e1fe)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/clz_ctz.c (ffffffff8185acb0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In lib/math/int_log.c (ffffffff81864bad)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - lib/math/int_log.c:intlog2
```
```
In lib/math/reciprocal_div.c (ffffffff81864df5)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In lib/sg_pool.c (ffffffff819277e0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b3244)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81a7e495)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux
```
```
In drivers/clk/clk-mux.c (ffffffff81a95733)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/dma/dmaengine.c (ffffffff81a98fb4)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e9d8)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/xen/mem-reservation.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81b21631)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28ee9)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81b331ea)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b62231)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:domain_update_iommu_superpage
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e7f3)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbe998)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff83951cf8)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/block/virtio_blk.c (ffffffff81bd2e3b)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be44be)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bff2cf)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81c3ca08)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c4349d)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-core.c (ffffffff81c58f68)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_xfer_mask2mode
```
```
In drivers/ata/libata-transport.c (ffffffff81c68e15)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-sata.c (ffffffff81c6aa52)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:__sata_set_spd_needed
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c82416)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_rotation
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_rotation
```
```
In drivers/spi/spi.c (ffffffff81cdae05)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff81d3e1ae)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81d45564)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81d95de5)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9b205)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81e2a5a0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3b816)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81e6cc56)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e966c6)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe53fa)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee0fd)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
```
In net/ipv4/udp.c (ffffffff83969d5d)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_pernet_init
```
```
In net/ipv4/fib_semantics.c (ffffffff820261ff)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In lib/flex_proportions.c (ffffffff821788fa)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
```
```
In lib/objpool.c (0)
Location: arch/x86/include/asm/bitops.h:361
Inline: True
```
</details>
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
In arch/arm64/kernel/setup.c (ffff8000114344ec)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/insn.c (ffff8000100964e4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
```
```
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e27c8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_get_mmio_region
```
```
In kernel/sched/core.c (ffff800010133aa4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffff800010140480)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffff80001016065c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffff8000101b63e0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffff80001021605c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffff80001022e7c8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230818)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/arraymap.c (ffff80001027ae00)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffff80001027d6b4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/events/ring_buffer.c (ffff8000102a2ae0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffff8000102bc1b8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffff8000102dbd34)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffff8000102e3510)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffff8000102e7a60)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffff80001030e3f0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffff80001034b430)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c79b0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103dba38)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/verity/enable.c (ffff800010411630)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffff800010412a24)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffff8000104453ec)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffff80001047f698)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffff800010492858)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffff800010507a3c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffff80001050ff08)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffff800010512670)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffff8000105f04b8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffff8000106195b0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/t10-pi.c (ffff80001061eb88)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffff8000106200a4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffff80001062b934)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffff800010633628)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/math/reciprocal_div.c (ffff80001063acd8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/sg_pool.c (ffff800010667770)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470d28)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff80001066d534)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (ffff80001066fbb4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010670b9c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_enable_quirk_socionext_synquacer
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/bus/brcmstb_gisb.c (ffff800011476a20)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069cc2c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bb064)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d25e4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/controller/pcie-rcar.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010723fd8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_free
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b854)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-mux.c (ffff8000107c5e78)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/sunxi/clk-sun9i-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f96e4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
```
```
In drivers/dma/dmaengine.c (ffff8000107fcd18)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f874)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff80001081006c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
```
```
In drivers/xen/mem-reservation.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffff80001088c45c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffff800010899324)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffff8000108af7e0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/base/regmap/regmap.c (ffff800010914678)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffff800011498658)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093d360)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffff800010957058)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffff800010989b6c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffff80001098bb24)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/ata/libata-core.c (ffff80001099eedc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_xfer_mask2mode
```
```
In drivers/ata/libata-transport.c (ffff8000109ae1f0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libahci_platform.c (ffff8000109bd8a0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
```
```
In drivers/spi/spi.c (ffff8000109c8238)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffff800010a20340)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffff800010a27638)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffff800010a72598)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a78b30)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/usb/host/xhci-mtk-sch.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/armada_thermal.c (ffff800010adda30)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b1b8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffff800010b2ec88)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67b00)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/of/base.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b78f9c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffff800010c31050)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c81854)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffff800010c884b4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/flex_proportions.c (ffff800010d88668)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/vfp/vfpsingle.c (c03065b0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/vfp/vfpsingle.c:__vfp_single_normaliseround
  - arch/arm/vfp/vfpsingle.c:vfp_single_normalise_denormal
```
```
In arch/arm/vfp/vfpdouble.c (c0308fb8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/vfp/vfpdouble.c:vfp_double_normaliseround
  - arch/arm/vfp/vfpdouble.c:vfp_double_normaliseround
  - arch/arm/vfp/vfpdouble.c:vfp_double_normalise_denormal
  - arch/arm/vfp/vfpdouble.c:vfp_double_normalise_denormal
```
```
In arch/arm/kernel/setup.c (c1504d3c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/atags_proc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/kernel/suspend.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/kernel/smp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/kernel/topology.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/kernel/vdso.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mm/dma-mapping.c (c031de68)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - arch/arm/mm/dma-mapping.c:__alloc_from_contiguous
```
```
In arch/arm/mm/mmu.c (c1508c54)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:late_alloc
```
```
In arch/arm/mm/cache-l2x0.c (c150a514)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2x0_cache_size_of_parse
```
```
In arch/arm/mm/cache-l2x0-pmu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mm/cache-uniphier.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/probes/uprobes/actions-arm.c (c0327f20)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/probes/uprobes/actions-arm.c:uprobes_substitute_pc
```
```
In arch/arm/net/bpf_jit_32.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-mvebu/mvebu-soc-id.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-mvebu/board-v7.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-mvebu/coherency.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-imx/cpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-imx/tzic.c (c030231c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - arch/arm/mach-imx/tzic.c:tzic_handle_irq
```
```
In arch/arm/mach-imx/mmdc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/id.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/timer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/omap_hwmod.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/omap_device.c (c033a7d0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/pm34xx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/pm44xx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/sr_device.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/prm_common.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/vc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-omap2/hsmmc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-tegra/pm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/mach-vexpress/spc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In arch/arm/plat-omap/dma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/fork.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/resource.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/umh.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/params.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/async.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/groups.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/core.c (c038318c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/cputime.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/fair.c (c03902b0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/debug.c (c03ad10c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/main.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/printk/printk.c (c152027c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/dma/mapping.c (c03e1040)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/direct.c (c03e1bfc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/contiguous.c (c03e2150)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_alloc_contiguous
```
```
In kernel/dma/coherent.c (c03e24c0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
```
```
In kernel/dma/virt.c (c03e28bc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/virt.c:dma_virt_alloc
```
```
In kernel/dma/remap.c (c03e29b0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_common_contiguous_remap
```
```
In kernel/profile.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/timekeeping.c (c03ee8bc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/time/ntp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/jiffies.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/time/timekeeping_debug.c (c0400020)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/futex.c (c1523698)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/acct.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/audit.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/relay.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/ftrace.c (c0454de8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (c046c8b4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_syscalls.c (c0479774)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:get_order
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/tnum.c (c04a9118)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_range
  - kernel/bpf/tnum.c:tnum_range
```
```
In kernel/bpf/hashtab.c (c04aa830)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (c04ace60)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/lpm_trie.c (c04aeea4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:longest_prefix_match
  - kernel/bpf/lpm_trie.c:longest_prefix_match
  - kernel/bpf/lpm_trie.c:longest_prefix_match
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/devmap.c (c04b7064)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/bpf/stackmap.c (c04baf04)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/cgroup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/events/core.c (c04c1a60)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/events/core.c:perf_adjust_period
  - kernel/events/core.c:perf_adjust_period
  - kernel/events/core.c:perf_adjust_period
  - kernel/events/core.c:perf_adjust_period
  - kernel/events/core.c:perf_adjust_period
  - kernel/events/core.c:perf_adjust_period
```
```
In kernel/events/ring_buffer.c (c04d2c24)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In kernel/padata.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In certs/system_keyring.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In certs/blacklist.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/mempool.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/page-writeback.c (c04e70b8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_min_pause
  - mm/page-writeback.c:wb_min_pause
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/readahead.c (c04eb270)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/shmem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/vmstat.c (c0501e40)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/percpu.c (c050828c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (c050bb34)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/workingset.c (c1530f40)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/gup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/memory.c (c05166e8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/vmalloc.c (c052c0bc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/page_alloc.c (c153207c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:alloc_pages_exact
```
```
In mm/memblock.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/zswap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/slub.c (c0549f10)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:free_loc_track
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
```
```
In mm/memcontrol.c (c0559ad8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/zpool.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/zbud.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In mm/memfd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/read_write.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/super.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/exec.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/pipe.c (c05769bc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/namei.c (c0578478)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In fs/select.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/dcache.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/file.c (c05903f0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/namespace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/xattr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/libfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fs-writeback.c (c05a4864)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/sync.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/buffer.c (c05b4da4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/aio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/io_uring.c (c05d6314)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/crypto/hooks.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/verity/enable.c (c05ddb70)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/hash_algs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/verity/open.c (c05ded6c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/verity/verify.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/verity/signature.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/binfmt_flat.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/coredump.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/array.c (c060a2a4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/proc/uptime.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/proc/vmcore.c (c0611fb4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/proc/vmcore.c:free_elfcorebuf
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/hash.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/indirect.c (c06398f0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/inline.c (c063adb8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/inode.c (c0640018)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (c0653ba8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/super.c (c0682e90)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/jbd2/journal.c (c0696ff0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ecryptfs/crypto.c (c06b5a6c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ecryptfs/messaging.c (c06badb0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/unicode/utf8-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/fuse/dir.c (c06c38d8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (c06cb708)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (c06cd788)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/pstore/ram.c (c06d6b70)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
```
```
In fs/pstore/ram_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In ipc/util.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In ipc/sem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In ipc/shm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/key.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/proc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/trusted.c (c06f0cac)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/commoncap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/security.c (c06f7784)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/ibpkey.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/digsig.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/platform_certs/load_uefi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/platform_certs/keyring_handler.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (c075f2a8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/ima/ima_modsig.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/api.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/aead.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/shash.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/acompress.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/cts.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/xts.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/deflate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/rng.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/bio.c (c0787e40)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-settings.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-mq.c (c079c808)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/blk-stat.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/genhd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/badblocks.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/bsg.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/mq-deadline.c (c07c40c8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/blk-integrity.c (c07c592c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (c07c6548)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (c07c7834)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In block/sed-opal.c (c07cd328)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
```
In lib/bitmap.c (c07d23c0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/clz_ctz.c (c07d9ab4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzdi2
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (c07d9f00)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (c07dbec0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/once.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/generic-radix-tree.c (c07ddd68)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/math/div64.c (c07e09cc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/math/int_sqrt.c (c07e0dcc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/math/reciprocal_div.c (c07e0f20)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/genalloc.c (c07ea700)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/reed_solomon/reed_solomon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/bch.c (c07f4b18)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/bch.c:init_bch
  - lib/bch.c:init_bch
  - lib/bch.c:decode_bch
  - lib/bch.c:find_poly_roots
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/nlattr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/mpi/mpicoder.c (c080c0ec)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
```
In lib/mpi/mpi-bit.c (c080c3e0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/mpi/mpi-bit.c:mpi_get_nbits
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/mpi/mpi-pow.c (c080df8c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/dim/dim.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/digsig.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/strncpy_from_user.c (c080f764)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c080f908)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/sg_split.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/sg_pool.c (c080ff38)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/irqchip/irq-al-fic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-alpine-msi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/exynos-combiner.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-tegra.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c154a060)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-gic-v2m.c (c0816510)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_unalloc_msi
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (c08182c4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_free_msi
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cf6c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_free_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_free_prop_table
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (c081d4bc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (c081db64)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare
```
```
In drivers/irqchip/irq-partition-percpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-crossbar.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-mtk-sysirq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-mtk-cirq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-imx-gpcv2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-aspeed-vic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/irq-meson-gpio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/irqchip/qcom-pdc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/bus/arm-cci.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/bus/brcmstb_gisb.c (c154eb70)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/omap_l3_smx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/bus/ti-sysc.c (c0827308)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_enable_module
  - drivers/bus/ti-sysc.c:sysc_enable_module
```
```
In drivers/bus/uniphier-system-bus.c (c0829650)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_add_bank
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/phy/phy-core-mipi-dphy.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/devicetree.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/pinconf-generic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/pinctrl-rza1.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/pinctrl-rza2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c08406a0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/berlin/berlin.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084e8d4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852244)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085bca4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/gpio/gpio-htc-egpio.c (c1550858)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/gpio/gpio-mvebu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/gpio/gpio-mxc.c (c086bb90)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
```
```
In drivers/gpio/gpio-stmpe.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/pci.c (c08834e4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c08891fc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:consistent_dma_mask_bits_show
  - drivers/pci/pci-sysfs.c:consistent_dma_mask_bits_show
  - drivers/pci/pci-sysfs.c:dma_mask_bits_show
  - drivers/pci/pci-sysfs.c:dma_mask_bits_show
```
```
In drivers/pci/vpd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/msi.c (c089f1b4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/ecam.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (c08a4cfc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/endpoint/pci-epf-core.c (c08a585c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/pci/endpoint/pci-epc-mem.c (c08a5f54)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/endpoint/pci-epc-mem.c:__pci_epc_mem_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_get_order
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_get_order
```
```
In drivers/pci/controller/pcie-cadence.c (c08a6064)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a72ac)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
```
```
In drivers/pci/controller/pci-mvebu.c (c08a8a18)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_set_window
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_set_window
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_set_window
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
```
```
In drivers/pci/controller/pcie-rcar.c (c08ae680)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b4888)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b586c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7ef4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/softcursor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/amba-clcd.c (c08de86c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/video/of_display_timing.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/ipmi/ipmi_dmi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/amba/bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-divider.c (c08efc08)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:_div_round_closest
  - drivers/clk/clk-divider.c:_div_round_closest
  - drivers/clk/clk-divider.c:_div_round_up
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-mux.c (c08f12ac)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (c08f239c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-aspeed.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-ast2600.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-highbank.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-hsdk-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-milbeaut.c (c08f50bc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/clk-milbeaut.c:m10v_mux_set_parent
```
```
In drivers/clk/clk-npcm7xx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/clk-qoriq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/actions/owl-factor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/berlin/berlin2-avpll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/berlin/berlin2-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/berlin/berlin2-div.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/berlin/bg2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/berlin/bg2q.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/hisilicon/clk.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/hisilicon/clkgate-separated.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/hisilicon/clk-hi3620.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/hisilicon/clk-hix5hd2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-busy.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-composite-8m.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-cpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-composite-7ulp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-divider-gate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-fixup-div.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-fixup-mux.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-frac-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-gate-exclusive.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-gate2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-pfd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-pfdv2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-pllv1.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-pllv2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-pllv4.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-sccg-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-imx6q.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-imx6sl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-imx6sll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-imx6sx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-imx6ul.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-imx7d.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/imx/clk-imx7ulp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mediatek/clk-mtk.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mediatek/clk-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mediatek/clk-gate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mediatek/clk-apmixed.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mediatek/clk-cpumux.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mediatek/reset.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mediatek/clk-mux.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/meson/clk-mpll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/meson/clk-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/meson/meson8b.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mvebu/common.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mvebu/clk-cpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/mvebu/clk-corediv.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-rz.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-r8a7740.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-r8a7778.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-r8a7779.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-sh73a0.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-mstp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/renesas/clk-div6.c (c09060ac)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/clk.c (c0906120)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_fractional_approximation
```
```
In drivers/clk/rockchip/clk-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/clk-cpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/clk-half-divider.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/clk-inverter.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/clk-mmc-phase.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/clk-muxgrf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/clk-ddr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/rockchip/softrst.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/samsung/clk.c (c090999c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/samsung/clk-pll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/samsung/clk-cpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/samsung/clk-exynos-clkout.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-audio-sync.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-divider.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-periph-fixed.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-periph-gate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-pll.c (c090ef24)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-pll.c:_get_table_rate
```
```
In drivers/clk/tegra/clk-pll-out.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-sdmmc-mux.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-super.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-emc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-bpmp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/tegra/clk-utils.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/clk.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/autoidle.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/dpll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/composite.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/divider.c (c158b840)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/ti/divider.c:ti_clk_divider_populate
  - drivers/clk/ti/divider.c:ti_clk_parse_divider_data
  - drivers/clk/ti/divider.c:ti_clk_parse_divider_data
```
```
In drivers/clk/ti/gate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/mux.c (c158c1cc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/ti/mux.c:of_ti_composite_mux_clk_setup
  - drivers/clk/ti/mux.c:ti_clk_build_component_mux
  - drivers/clk/ti/mux.c:of_mux_clk_setup
```
```
In drivers/clk/ti/apll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/clkt_dpll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/clkctrl.c (c158cee0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
```
```
In drivers/clk/ti/dpll3xxx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/fapll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/interface.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/clk-dra7-atl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/ti/adpll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/versatile/icst.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/versatile/clk-icst.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clk/versatile/clk-sp810.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/dmaengine.c (c091e120)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/of-dma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/amba-pl08x.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/tegra20-apb-dma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/ti/edma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/ti/omap-dma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma/ti/dma-crossbar.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/dove/pmu.c (c0933e8c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:pmu_irq_handler
```
```
In drivers/soc/imx/soc-imx8.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/amlogic/meson-clk-measure.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/amlogic/meson-gx-socinfo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/amlogic/meson-mx-socinfo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/qcom/smem_state.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/renesas/renesas-soc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/renesas/rcar-sysc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/renesas/rmobile-sysc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/samsung/exynos-chipid.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/samsung/pm_domains.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/tegra/pmc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/soc/tegra/powergate-bpmp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c0989d80)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/max310x.c (c0994920)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/tty/serial/imx.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/random.c (c09aadf8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm1.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (c09bfad4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_iova_to_phys
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pages
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/ipmmu-vmsa.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/omap-iommu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/tegra-gart.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/regmap/regmap.c (c09fa8c0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache.c (c09fde58)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:get_order
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/soc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/block/loop.c (c1598ef8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/misc/vexpress-syscfg.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/sm501.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/t7l66xb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/tc6387xb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/tc6393xb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (c0a25dd8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/sd.c (c0a5bc64)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (c0a5dee8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/scsi/sg.c (c0a632c4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/ata/libata-core.c (c0a6f508)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_xfer_mask2mode
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/ata/libata-transport.c (c0a7d52c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/ata/libahci_platform.c (c0a886b0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
```
```
In drivers/ata/sata_highbank.c (c0a89184)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/mtdcore.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/mtdconcat.c (c0a928ac)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/mtdpart.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/mtdchar.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/parsers/cmdlinepart.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/parsers/ofpart.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/mtd_blkdevs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/mtdblock.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/nand/core.c (c0a99810)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mtd/nand/core.c:nanddev_init
  - drivers/mtd/nand/core.c:nanddev_init
```
```
In drivers/mtd/nand/bbt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/nand/raw/nand_base.c (c0aa1e8c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_scan_tail
```
```
In drivers/mtd/nand/raw/nand_bbt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/nand/raw/nand_onfi.c (c0aa6668)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect
  - drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect
```
```
In drivers/mtd/nand/raw/nand_jedec.c (c0aa69d8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_jedec.c:nand_jedec_detect
  - drivers/mtd/nand/raw/nand_jedec.c:nand_jedec_detect
```
```
In drivers/mtd/nand/raw/nand_hynix.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/nand/raw/nand_micron.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mtd/nand/raw/nand_bch.c (c0aa8d0c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_bch.c:nand_bch_init
  - drivers/mtd/nand/raw/nand_bch.c:nand_bch_init
  - drivers/mtd/nand/raw/nand_bch.c:nand_bch_init
```
```
In drivers/spi/spi.c (c0aadb44)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/spi/spi-mem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad77e0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
```
```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad9ccc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/auxdisplay/arm-charlcd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/hub.c (c0aeb894)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/urb.c (c0af75ac)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/config.c (c0afd8b4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/devio.c (c0b02614)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/phy/phy-ulpi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (c0b29430)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/host/xhci.c (c0b485d4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (c0b4d4b4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_microframes_to_exponent
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b5fc20)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:setup_sch_info
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/musb/musb_host.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/musb/musb_gadget.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/gadget/udc/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/usb/roles/class.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/evdev.c (c0b7f230)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/rtc/nvmem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/i2c/busses/i2c-s3c2410.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/media/cec/cec-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/pps/kapi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/of-thermal.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/thermal/armada_thermal.c (c0bbf630)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_read_sensor
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-init.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/md/dm-kcopyd.c (c0be93b0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/edac/edac_mc.c (c0bee438)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/edac_device.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/opp/ti-opp-supply.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpufreq/cpufreq-dt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpuidle/governors/menu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpuidle/governors/teo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpuidle/coupled.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpuidle/cpuidle-big_little.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/cpuidle/cpuidle-psci.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/core.c (c0c0a160)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/core/queue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/host/mmci.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/qcom_scm-32.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/arm_scmi/bus.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/efi/memmap.c (c15a8b14)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/firmware/tegra/bpmp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/sh_cmt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/sh_mtu2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/renesas-ostm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/sh_tmu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/mmio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/dw_apb_timer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/timer-rockchip.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b59c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/clocksource/timer-imx-gpt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/of/base.c (c0c4de64)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In drivers/of/device.c (c0c4f9ec)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/of/device.c:of_dma_configure
  - drivers/of/device.c:of_dma_configure
  - drivers/of/device.c:of_dma_configure
```
```
In drivers/of/platform.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/of/dynamic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/of/fdt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/of/irq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/of/of_reserved_mem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (c0c5e8dc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/devfreq/governor_simpleondemand.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/memory/samsung/exynos-srom.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/memory/tegra/mc.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/perf/arm_pmu.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/sound_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/sound.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/init.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/control.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/device.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/info.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/sound_oss.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/vmaster.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/jack.c (c0c8b5d0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - sound/core/jack.c:snd_jack_set_key
```
```
In sound/core/timer.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/pcm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/pcm_native.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/pcm_lib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/pcm_memory.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/memalloc.c (c0c9bea4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - sound/core/memalloc.c:snd_dma_alloc_pages_fallback
```
```
In sound/core/pcm_dmaengine.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/core/compress_offload.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/soc-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/soc-dapm.c (c0caab0c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dapm_put_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_get_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_add_path
```
```
In sound/soc/soc-pcm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/soc-ops.c (c0cb6570)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - sound/soc/soc-ops.c:snd_soc_get_volsw_range
  - sound/soc/soc-ops.c:snd_soc_put_volsw_range
  - sound/soc/soc-ops.c:snd_soc_put_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_get_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_put_volsw
  - sound/soc/soc-ops.c:snd_soc_get_volsw
```
```
In sound/soc/soc-topology.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/soc-ac97.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/codecs/sgtl5000.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/fsl/fsl_ssi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/fsl/imx-audmux.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In sound/soc/fsl/imx-pcm-fiq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/sock.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/scm.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/sysctl_net_core.c (c0ce113c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/ethtool.c (c0cf4024)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/dst.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/neighbour.c (c0d00e08)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/filter.c (c0d19fa4)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/sock_map.c (c0d37554)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/core/bpf_sk_storage.c (c0d48548)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5bdf8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/inet_hashtables.c (c0d78d1c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_input.c (c0d852ec)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (c0d908b8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (c0d97ae0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_metrics.c (c0da087c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/udp.c (c15b7eac)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/fib_semantics.c (c0dc259c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
```
```
In net/ipv4/fib_trie.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/metrics.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/tcp_cubic.c (c0ddcf7c)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/xfrm/xfrm_hash.c (c0df1ae8)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/packet/af_packet.c (c0e5bc64)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In net/xdp/xsk_queue.c (c0e7bc70)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xskq_create
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/flex_proportions.c (c0e834dc)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/kobject.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
```
In lib/string.c (c0e8f670)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/vsprintf.c (0)
Location: include/asm-generic/bitops/builtin-fls.h:12
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/setup-common.c (c00000000134a4fc)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/setup_64.c (c00000000134ad28)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:parse_cache_info
```
```
In arch/powerpc/sysdev/mpic.c (c000000001358ae0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/sysdev/msi_bitmap.c (c0000000000b7be8)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_reserve_dt_hwirqs
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs
```
```
In arch/powerpc/sysdev/xive/native.c (c0000000000c0200)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_alloc_vp_block
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e366c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
```
```
In arch/powerpc/platforms/pseries/msi.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In kernel/sched/core.c (c00000000017eccc)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (c00000000018f6b4)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (c0000000001b6908)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/time/timekeeping_debug.c (c00000000021bb5c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (c000000000297d38)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (c0000000002b7db0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002baf44)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In kernel/bpf/arraymap.c (c000000000324280)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (c000000000327150)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:longest_prefix_match
  - kernel/bpf/lpm_trie.c:longest_prefix_match
  - kernel/bpf/lpm_trie.c:longest_prefix_match
```
```
In kernel/bpf/devmap.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In kernel/events/ring_buffer.c (c000000000354d80)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (c0000000003739f0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (c00000000039b864)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (c0000000003a2e00)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (c0000000003a98dc)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (c0000000003df154)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (c00000000042a9cc)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In fs/fs-writeback.c (c0000000004c96e0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c0000000004e0e54)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In fs/verity/enable.c (c00000000051f0a4)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (c000000000520574)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (c00000000055ad68)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (c0000000005a435c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (c0000000005baf40)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (c00000000064d124)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (c000000000657724)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (c00000000065a318)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (c000000000786e0c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (c0000000007b8d68)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In block/t10-pi.c (c0000000007be09c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (c0000000007bf784)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (c0000000007cdde8)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (c0000000007d8910)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In lib/math/reciprocal_div.c (c0000000007e1dc0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In lib/sg_pool.c (c00000000081ccd4)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000835280)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In drivers/dma/dmaengine.c (c0000000008c8224)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c000000000935114)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In drivers/char/random.c (c0000000009477e8)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/base/regmap/regmap.c (c0000000009b66f8)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (c0000000013abba4)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5150)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (c000000000a04e78)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (c000000000a49e9c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (c000000000a4c870)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/ata/libata-core.c (c000000000a6341c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (c000000000a75280)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (c000000000a835dc)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8ee4)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/urb.c (c000000000ada6ac)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (c000000000ae3560)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (c000000000b47e08)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (c000000000b4ff78)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In drivers/md/dm-kcopyd.c (c000000000bfe0e0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (c000000000c286ac)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/of/base.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In net/core/bpf_sk_storage.c (c000000000d2b2ac)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8c78c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (c000000000d9598c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In net/ipv4/udp.c (c0000000013c3dbc)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
```
```
In lib/flex_proportions.c (c000000000ec8d7c)
Location: arch/powerpc/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
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
In kernel/sched/core.c (ffffffe0000e636e)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffe0000ee436)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffe000104ce0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/time/timekeeping_debug.c (ffffffe00013c180)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffe000175c28)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe000189198)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffe0001b2af4)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffe0001b4940)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:longest_prefix_match
  - kernel/bpf/lpm_trie.c:longest_prefix_match
  - kernel/bpf/lpm_trie.c:longest_prefix_match
```
```
In kernel/bpf/devmap.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffe0001d1684)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffe0001de2ae)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffe0001f4d8c)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/percpu.c (ffffffe0001f78ac)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In mm/slab_common.c (ffffffe0001fd58c)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffe000215146)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - mm/vmalloc.c:lazy_max_pages
```
```
In mm/slub.c (ffffffe00023ca40)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In fs/fs-writeback.c (ffffffe00028659e)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffe0002940b8)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In fs/verity/enable.c (ffffffe0002b9834)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffe0002ba648)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffe0002db304)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffe000307ee4)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffe0003174f0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffe000373878)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffe00037a75c)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffe00037c69a)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffe00042f378)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffe00044f258)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffe00045097a)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffe000451b4a)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffe0004527b8)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffe00045bb0c)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffe000461560)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffe000467292)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In lib/sg_pool.c (ffffffe000492da6)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0d88)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffe0005133ba)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffe000517564)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555c60)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffe00055bca2)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffe0005630c8)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/base/regmap/regmap.c (ffffffe000595b1c)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffe000031db4)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1504)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c6156)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffe0005edd5e)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005f01c2)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/ata/libata-core.c (ffffffe0005fa512)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_mode_string
  - drivers/ata/libata-core.c:ata_xfer_mask2mode
```
```
In drivers/ata/libata-transport.c (ffffffe00060b0e4)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffe000613e30)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c408)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/core/urb.c (ffffffe00064365a)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffe00064937e)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffe00068ac48)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000690592)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f97a0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffe000708436)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/of/base.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7990)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3670)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9a34)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In net/ipv4/udp.c (ffffffe00004185a)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
```
```
In lib/flex_proportions.c (ffffffe0008b269a)
Location: include/asm-generic/bitops/fls.h:13
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045047)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104668d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049bf3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b1c5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104be22)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c36e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066ae9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810cd77d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810da7c9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810f50fb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff811421e5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811957e1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff811a94f6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab217)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811eecc3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811f09a4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8121064f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81224dc2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff8123ff1c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff81244e2b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff81248f84)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff81270484)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff812a1f21)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130aedf)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8131b026)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/verity/enable.c (ffffffff81347ff9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81349077)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff81371492)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff813a2825)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813b4310)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8141c8db)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81424609)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff814265d8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814e9602)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff8150ceb7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff8150ef06)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8150fc7c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81510cd3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff8151a4bc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81521290)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff81526d20)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff81552aa6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a62da)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff8161a7cb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff8161cca5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff8162bf14)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff816769d1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8167b597)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81684497)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816aee07)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8868)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816e6213)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff828f0be2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a45d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8173769e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff817396d3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/nvme/host/core.c (ffffffff81744da5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_cmd
```
```
In drivers/nvme/host/pci.c (ffffffff81750df7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/ata/libata-core.c (ffffffff8175af87)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81767395)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81774e15)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/usb/core/urb.c (ffffffff817a8b80)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817aebd2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff817ecfb5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f3295)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff8185a232)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff81878e28)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81892295)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8192982f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8196ec18)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81975965)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e826)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82906c88)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a4dd05)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034557)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103590d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81038f34)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a63e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b00e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b7bf)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056eb9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810bbffd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810c97d9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810e52bb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff81135545)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811888f1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff8119c476)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e520)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811e1a53)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811e36f4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff812033df)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81217f5c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff81232f1c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff81237b2f)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff8123bf34)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff812623f4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff81293a01)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fbaf9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130bbc6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/verity/enable.c (ffffffff81338cd9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81339d57)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff81361f22)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff813932b5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a4da0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8140d35b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81415089)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81417058)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814d9b72)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff814fd2e7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814ff336)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814fff9c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81500ff3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff8150a7ac)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81511580)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff81517000)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff81542d86)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff8159547a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
```
In drivers/clk/clk-mux.c (ffffffff8160ecfb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff81611395)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81655ab1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8165a687)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff81662117)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168c767)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816964a8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816c0853)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff828e8022)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff816ddedd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8171933e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b373)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/nvme/host/core.c (ffffffff81726a35)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_cmd
```
```
In drivers/nvme/host/pci.c (ffffffff81730c97)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/ata/libata-core.c (ffffffff8173ae27)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff817471f5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81754bc5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782fd9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/urb.c (ffffffff8179a590)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817a05d2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff817b20c5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b8435)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff81821836)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff818e35df)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81928708)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f425)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819382e6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff828fefd6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a0adf5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044e87)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810464cd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049a33)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b005)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bc62)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c1ae)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066f99)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810ccbdd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810d6b49)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810f22fb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff81140095)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811935b1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff811a72c6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8fe7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811eca93)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811ee774)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8120e3ef)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81222b62)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff8123dcbc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff81242bcb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff81246d24)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff8126e224)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff8129fd31)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81308ccf)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81318af6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/verity/enable.c (ffffffff81345ac9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81346b47)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff8136ef62)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff813a0085)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813b1b70)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff81418a7b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814207a9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81422778)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814e5692)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff81508f47)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff8150af96)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8150bd0c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff8150cd63)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff8151654c)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff8151d320)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff81522db0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff8154e7e6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a686a)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff816485ab)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff8164ac45)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff8165a024)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff816a4da1)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff816a9977)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff816b2867)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dcfe7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6d38)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff817133a3)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff82904734)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81735047)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff8174922d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81777e2e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779e63)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/ata/libata-core.c (ffffffff8178acf0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff81797155)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff817a51b5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdda9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/urb.c (ffffffff817e5620)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817eb672)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff81829a85)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8182fd65)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a9862)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff818ca2c8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e5d95)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a9bf)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d93e8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0135)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8ff6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8291c56b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81aba0f5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046287)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810478cd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:detect_ht
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ae43)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c415)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d072)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d5be)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81068579)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_id_is_primary_thread
```
```
In kernel/sched/core.c (ffffffff810d561d)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/fair.c (ffffffff810e2459)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/debug.c (ffffffff810fd2eb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/time/timekeeping_debug.c (ffffffff8114cbc5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
```
In kernel/trace/ftrace.c (ffffffff811a1181)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
```
```
In kernel/trace/tracing_map.c (ffffffff811b5066)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6e27)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811faf33)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (ffffffff811fcc44)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8121d2ff)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81231d42)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_writeout_inc
```
```
In mm/vmstat.c (ffffffff8124d3ec)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/percpu.c (ffffffff812520bd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff81256554)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_slab
```
```
In mm/vmalloc.c (ffffffff8127dbe2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/slub.c (ffffffff812afe71)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131a981)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8132a716)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In fs/verity/enable.c (ffffffff81358da9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81359e27)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/array.c (ffffffff813828f2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
```
In fs/ext4/inode.c (ffffffff813b40a9)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813c66b4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dir.c (ffffffff8142f7eb)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814375ad)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff814395a8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814fe5f2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff815226e7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81524636)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff815253ac)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81526443)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/bitmap.c (ffffffff8152fcdc)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/clz_ctz.c (ffffffff81536b90)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzsi2
```
```
In lib/kfifo.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/math/reciprocal_div.c (ffffffff8153c730)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/math/reciprocal_div.c:reciprocal_value_adv
  - lib/math/reciprocal_div.c:reciprocal_value
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/sg_pool.c (ffffffff81568636)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_pool_alloc
  - lib/sg_pool.c:sg_pool_free
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff81662b3b)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
```
```
In drivers/dma/dmaengine.c (ffffffff816651e5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/xen/mem-reservation.c (ffffffff816745f4)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff816bf201)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff816c3dd7)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_ist
```
```
In drivers/char/random.c (ffffffff816ccd87)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/char/random.c:add_timer_randomness
```
```
In drivers/iommu/amd_iommu.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f7d17)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701438)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff8172e593)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff8290a473)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750487)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
  - drivers/mfd/twl4030-irq.c:twl4030_sih_bus_sync_unlock
```
```
In drivers/nvdimm/region_devs.c (ffffffff817646ad)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81791c4e)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793c93)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/ata/libata-core.c (ffffffff817a4b40)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:ata_down_xfermask_limit
  - drivers/ata/libata-core.c:__sata_set_spd_needed
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-transport.c (ffffffff817b0fc5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_link_sata_spd_limit
  - drivers/ata/libata-transport.c:show_ata_link_hw_sata_spd_limit
```
```
In drivers/spi/spi.c (ffffffff817bf035)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e8049)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/core/urb.c (ffffffff817ff880)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff818058b2)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff81843a25)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_last_valid_endpoint
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81849f05)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
```
```
In drivers/input/evdev.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c4ebd)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/mmc/core/core.c (ffffffff818e6de8)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81902a15)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In net/core/sysctl_net_core.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8199ceef)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e3048)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9df5)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2d56)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82922fe6)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81ac6545)
Location: arch/x86/include/asm/bitops.h:324
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
```
</details>
</li>
</ul>

## Differences
