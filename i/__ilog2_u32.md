# Function: <code>__ilog2_u32</code>

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
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b2196)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81185ab7)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In mm/page-writeback.c (ffffffff81198d92)
Location: include/linux/log2.h:32
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
In mm/slub.c (ffffffff811edab3)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8123a5ec)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81244cc0)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
```
```
In fs/ext4/inode.c (ffffffff81297696)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff81313356)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81317015)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
```
```
In fs/fuse/inode.c (ffffffff8131bcfe)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff813c4950)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In block/blk-integrity.c (ffffffff813e7b5b)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/flex_proportions.c (ffffffff813e9781)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu_max
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153d477)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/scsi/sd.c (ffffffff815bdc63)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf7e8)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_complete
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81610413)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8177994c)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:32
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
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b4c66)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81197b34)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In mm/page-writeback.c (ffffffff811addd7)
Location: include/linux/log2.h:32
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
In mm/slub.c (ffffffff8120cf3c)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8126234c)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8126d880)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812c4cd7)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff813478d3)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8134ecaf)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff813507ee)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81408af9)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In block/blk-integrity.c (ffffffff8142ddeb)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/flex_proportions.c (ffffffff8142fed6)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815920e9)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff815b9099)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff815f076f)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81616afb)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_dif.c (ffffffff816181f2)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff8166ffef)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6b1c)
Location: include/linux/log2.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:32
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:32
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
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810bc2aa)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811a7510)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811be4b9)
Location: include/linux/log2.h:26
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
In mm/slub.c (ffffffff8121ef9c)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8127584f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81280ad0)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812da394)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8135d1f8)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff813645bd)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8136614e)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81423657)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-integrity.c (ffffffff81447bab)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/flex_proportions.c (ffffffff8144c106)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bf9a9)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff815e833f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161d6a3)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff816465ad)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_dif.c (ffffffff81647d92)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648bf7)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff8169dccd)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8181720c)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:retransmits_timed_out
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/udp.c (ffffffff820297c0)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:26
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
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b6d0a)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8119cac0)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811aecb2)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811c785b)
Location: include/linux/log2.h:26
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
In mm/slub.c (ffffffff8122b64f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
```
In fs/file.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81282d8b)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8128e390)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812fe23f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff81371c7d)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81378d98)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8137a80e)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81431a4b)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/blk-integrity.c (ffffffff814560e6)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d554a)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff815fcab8)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff81631b2f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8165b123)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d526)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff816b31c4)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fc6f)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8210cd5a)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/flex_proportions.c (ffffffff818ec8b6)
Location: include/linux/log2.h:26
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
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810be07a)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811ac543)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811c2842)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811dc69b)
Location: include/linux/log2.h:26
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
In mm/slub.c (ffffffff81246d5c)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
```
In fs/file.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a58db)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812b0f9d)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff81322a2f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8139697d)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8139dc38)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8139f6ae)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff8145d3c2)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/blk-integrity.c (ffffffff81481d46)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c2fa)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff81664c58)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169a48f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff816c47b5)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6b7c)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff8171e851)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf00f)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8271706e)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81972886)
Location: include/linux/log2.h:26
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
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810c5da8)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811c3b45)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/sockmap.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811e2b93)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff811fe9a1)
Location: include/linux/log2.h:26
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
In mm/slub.c (ffffffff8126812f)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cc657)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812d8e22)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8135040a)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff813c5504)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff813cd008)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff813cea3e)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff81490e64)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/deadline-iosched.c (ffffffff814ada2e)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814b6996)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/blk-zoned.c (ffffffff814b8003)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677848)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816a0586)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d675d)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81700cd4)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sd_zbc.c (ffffffff81702fde)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff8175d28d)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914bd0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/udp.c (ffffffff827414b0)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/flex_proportions.c (ffffffff819cecb6)
Location: include/linux/log2.h:26
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
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In arch/x86/kernel/tce_64.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ce748)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811d56e5)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811f3003)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8120f1a6)
Location: include/linux/log2.h:26
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
In mm/slub.c (ffffffff8127dc4b)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e1887)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812ee2f2)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8136876d)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff813de6a4)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff813e6390)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff813e7eb8)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814a9cfb)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff814c81a4)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814ca1a6)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814cafe3)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In block/blk-zoned.c (ffffffff814cbaf3)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/intel-pasid.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696928)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816c0d33)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f853c)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81723da8)
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
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
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81781805)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81934738)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943382)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/ipv4/udp.c (ffffffff828fb716)
Location: include/linux/log2.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:26
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a08176)
Location: include/linux/log2.h:26
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
In kernel/sched/fair.c (ffffffff810d6af5)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811e9f43)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8120ad1f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8121ecd2)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff81299a81)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fffc1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130fac6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813918b5)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff81409bc3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814122e9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81413f58)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814d7ca6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff814f6a27)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814f8a76)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814f9905)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In block/blk-zoned.c (ffffffff814fa793)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf238)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816fbb33)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff81731bfd)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8175efc8)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff817bfe20)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81998278)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f055)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7926)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82918115)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a77ac5)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810e0619)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811f66a3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81217fff)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8122c772)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff812a9941)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813128ff)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81322a46)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (ffffffff8134fa19)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81350a97)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff813aa245)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff814242fb)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8142c029)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8142dff8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814f1022)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff815148d7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81516926)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8151769c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff815186f3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3078)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff8171fee3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755d6d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81782fae)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff817f07a0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff819899bf)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819ceda8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5af5)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de9b6)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82921f84)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81aaeeb5)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810e9db9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81219c93)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81243b4f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81258606)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_stat_error
  - mm/page-writeback.c:__add_wb_stat
```
```
In mm/slub.c (ffffffff812de965)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81348c60)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:__add_wb_stat
```
```
In fs/buffer.c (ffffffff81359230)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_size_bits
```
```
In fs/io_uring.c (ffffffff8137cd57)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff8139627e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff8139749b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff813f6cf2)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8147225e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_fillattr
```
```
In fs/fuse/file.c (ffffffff81475d10)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fuse/inode.c (ffffffff8147dc9f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff81542f9b)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-mq.c (ffffffff8154e306)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:queued_to_index
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff815756cb)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-integrity.c (ffffffff8157714a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81577e5c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81578950)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/keyslot-manager.c (ffffffff8158112a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff81581d01)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff815e8b36)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aae9d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/base/regmap/regmap.c (ffffffff817dbff3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff818154a4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff818420e0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sectors_to_logical
  - drivers/scsi/sd.c:bytes_to_logical
  - drivers/scsi/sd.c:logical_to_sectors
```
```
In drivers/scsi/sd_zbc.c (ffffffff81849771)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sectors_to_logical
  - drivers/scsi/sd_zbc.c:logical_to_sectors
```
```
In drivers/usb/core/urb.c (ffffffff818bfd6a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81a616d6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81abaee4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2135)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb6e1)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82d2e53c)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810f1221)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/printk/printk.c (ffffffff82fdc6c5)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8121c4b3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81230416)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8124e1df)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff812657ca)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff812ea77b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81359028)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81369825)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (ffffffff8138b537)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff813a7f9e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff813a8f0b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff8140952e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8148cb31)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_fillattr
```
```
In fs/fuse/file.c (ffffffff81496bfc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81499019)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff81560315)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff8156cc16)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/mq-deadline.c (ffffffff815926ed)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-integrity.c (ffffffff81593de4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81594adc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81595698)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/keyslot-manager.c (ffffffff8159e147)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff8159ecf1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff8160dbe6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8256)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff817f10ca)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff81824694)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8185328b)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff818cc8bc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ac6284)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdd67)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7686)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8301d0dc)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810f3528)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/printk/printk.c (ffffffff831e7423)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8121fed2)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812259f8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81252b13)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8126a2cc)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff812f1f22)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8135fb80)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81370635)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (ffffffff81392723)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff813aeffe)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff813aff7b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff8140f6ce)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff81493b53)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff8149bd00)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8149e249)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff815683e9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff81574ab6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/mq-deadline.c (ffffffff8159950f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
```
```
In block/blk-integrity.c (ffffffff8159abc4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8159b8af)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff8159c2ec)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/keyslot-manager.c (ffffffff815a4e9f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff815a5b5d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff815f1336)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81708822)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b3a6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff817d5967)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff818078bd)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81836cab)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff818aff2e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab1498)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8e17)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff832281c1)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff8110cd88)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/printk/printk.c (ffffffff832cb589)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8125826a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125da01)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8128e3e1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a6f66)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff8133aed8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813ae48e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff813bf1ac)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (ffffffff813e09b9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/verity/enable.c (ffffffff813febae)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff813ffb6b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff814626a7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff814eafbc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814f36e6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff814f60f9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff81502b59)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff815cc9eb)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff815d8fd9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/mq-deadline.c (ffffffff8160183f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81602e04)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81603846)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff816045e3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/keyslot-manager.c (ffffffff8160d91f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In block/blk-crypto.c (ffffffff8160e63c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff8165e4a6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81784642)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823ed0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff81860ed8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff818921ad)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818c4489)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff819450d6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81a0629e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio_end
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b6e454)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76062)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff833125d6)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff811288d8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/printk/printk.c (ffffffff8347ec77)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff81172d60)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff812a0f23)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7d51)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff812e3261)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/page-writeback.c (ffffffff812ff168)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff813ad7aa)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81432747)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81446022)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/verity/enable.c (ffffffff81472742)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff814738ed)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff814e1862)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff81579adf)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81583139)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81585db6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff81594113)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/dh.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff816795e9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff81686d63)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/mq-deadline.c (ffffffff816b414d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff816b5d44)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff816b6a46)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff816b7d31)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - block/blk-zoned.c:__blk_req_zone_write_unlock
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-crypto.c (ffffffff816c1cf6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff816c21f7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff81e8ed55)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81777c0a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb309)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195966c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81963703)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff819a8b45)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff819dc449)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81a10d24)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff81a9d723)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81b6df33)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81cfdb3a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81d059d2)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff834cc6b1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37d4f)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff81151fa8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/printk/printk.c (ffffffff83eaad12)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff811aa86e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff812fdce1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813063d4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8134b8d1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/page-writeback.c (ffffffff81369887)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/slub.c (ffffffff8142da1a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814c04a5)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814d4fa2)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/verity/enable.c (ffffffff81504432)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81505883)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff8157ab78)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8161f17f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff816290c9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8162bfe6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff8163cce3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/dh.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff81735abd)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff81744a33)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/mq-deadline.c (ffffffff81773c49)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81775804)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff81776a06)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81778336)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff817834f7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff81789fdf)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09dc9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0fd3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acc7f1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1bc13)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b57a0f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81b90f7f)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff81c227f3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d0a401)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec279a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecab12)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff83f0f0de)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_pernet_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81f001af)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In lib/flex_proportions.c (ffffffff820208da)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff8116188d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/printk/printk.c (ffffffff836cfcd2)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff811bc7ae)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8132c8f1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81335220)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8137c921)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/page-writeback.c (ffffffff8139ba24)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/slub.c (ffffffff8146309a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814f5895)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8150af84)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/verity/enable.c (ffffffff8153bbc3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff8153cb25)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff815b0c42)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff816575a4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff816612eb)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81664226)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff816751f3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/dh.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff81771fed)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/mq-deadline.c (ffffffff817b3f2b)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff817b65d6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff817b7be0)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff817c3851)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff817ca8ef)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52c59)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0d841)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19383)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6aca9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/virtio_blk.c (ffffffff81b7efcb)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
```
```
In drivers/nvdimm/region_devs.c (ffffffff81baaf8f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81be69f8)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff81c89770)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d7353b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f20cfa)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81f295bc)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff837356ed)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_pernet_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5fc2f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In lib/flex_proportions.c (ffffffff820a091a)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff8116fae0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/printk/printk.c (ffffffff839010e2)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/update.c (ffffffff811cd3e8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81350e31)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/bloom_filter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81359880)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff813a5b7e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/watch_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c445d)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/slub.c (ffffffff8145f2ea)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/pipe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81529fa2)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/verity/enable.c (ffffffff81570ea3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81571f85)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff815e9ae9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8168f69f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_fillattr
```
```
In fs/fuse/file.c (ffffffff8169b1ab)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff8169e3f3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/util.c (ffffffff816b15b3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/dh.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (ffffffff817b3243)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-core.c:blk_check_zone_append
```
```
In block/mq-deadline.c (ffffffff817f7ad4)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff817fafe6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff817fc934)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In block/blk-crypto-profile.c (ffffffff818084e1)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff8180e1fe)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e9d8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b62231)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e7f3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbe998)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/virtio_blk.c (ffffffff81bd2e3b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bff2cf)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81c3ca08)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c82416)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_rotation
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_rotation
```
```
In drivers/usb/core/urb.c (ffffffff81d3e1ae)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81e2a5a0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe53fa)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee0fd)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff83969d5d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp_pernet_init
```
```
In net/ipv4/fib_semantics.c (ffffffff820261ff)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
```
In lib/flex_proportions.c (ffffffff821788fa)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
```
```
In lib/objpool.c (0)
Location: include/linux/log2.h:22
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
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e27c8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_get_mmio_region
```
```
In kernel/sched/fair.c (ffff800010140480)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffff80001027ae00)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffff8000102a2ae0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffff8000102bc1b8)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffff80001034b430)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c79b0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103dba38)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (ffff800010411630)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffff800010412a24)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffff80001047f698)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffff800010507a3c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffff80001050ff08)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffff800010512670)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffff8000105f04b8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffff8000106195b0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/t10-pi.c (ffff80001061eb88)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffff8000106200a4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010670b9c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_enable_quirk_socionext_synquacer
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/pcie-rcar.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/sunxi/clk-sun9i-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f96e4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f874)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff80001081006c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
```
```
In drivers/base/regmap/regmap.c (ffff800010914678)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffff800010957058)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffff800010989b6c)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffff800010a20340)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mtk-sch.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffff800010c31050)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c81854)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffff800010c884b4)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffff800010d88668)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/vfp/vfpsingle.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/vfp/vfpdouble.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/kernel/atags_proc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/kernel/suspend.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/kernel/smp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/kernel/topology.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/kernel/vdso.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mm/mmu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mm/cache-l2x0.c (c150a514)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2x0_cache_size_of_parse
```
```
In arch/arm/mm/cache-l2x0-pmu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mm/cache-uniphier.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/net/bpf_jit_32.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-mvebu/mvebu-soc-id.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-mvebu/board-v7.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-mvebu/coherency.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-imx/cpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-imx/mmdc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/id.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/timer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/omap_hwmod.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/omap_device.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/pm34xx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/pm44xx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/sr_device.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/prm_common.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/vc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-omap2/hsmmc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-tegra/pm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/mach-vexpress/spc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/arm/plat-omap/dma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/resource.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/umh.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/params.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/async.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/groups.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/fair.c (c03902b0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/main.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/console.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/dma/mapping.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/dma/contiguous.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/dma/coherent.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/dma/virt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/dma/remap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/ntp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/jiffies.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_stat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_printk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (c04ace60)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (c04d2c24)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In certs/system_keyring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In certs/blacklist.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/page-writeback.c (c04e70b8)
Location: include/linux/log2.h:22
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
In mm/readahead.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/page_alloc.c (c1532134)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/memblock.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/dmapool.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/slub.c (c054f444)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/vmpressure.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/zpool.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/zbud.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/char_dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (c05a4864)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/sync.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/buffer.c (c05b4da4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/block_dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (c05ddb70)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/hash_algs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/open.c (c05ded6c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/verity/verify.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/signature.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/binfmt_flat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/self.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/thread_self.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/kernfs/mount.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/kernfs/symlink.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/sysfs/dir.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/hash.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/indirect.c (c06398f0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/inline.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/inode.c (c0640018)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (c064ee28)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/super.c (c0682e90)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/jbd2/journal.c (c0696ff0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
```
```
In fs/squashfs/block.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/dir.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/namei.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/super.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/decompressor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/page_actor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/xattr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ramfs/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ecryptfs/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/unicode/utf8-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fuse/dir.c (c06c38d8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (c06cb708)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (c06cd788)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/fuse/acl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/pstore/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/pstore/ram.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/pstore/ram_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/efivarfs/inode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/efivarfs/super.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/proc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/security.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/netnode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/netport.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/ibpkey.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/smack/smack_access.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/tomoyo/audit.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/tomoyo/memory.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/device_cgroup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/digsig.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/platform_certs/load_uefi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/platform_certs/keyring_handler.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/ima/ima_modsig.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/cipher.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/aead.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/acompress.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/gf128mul.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/deflate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/rng.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-settings.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-mq.c (c079c808)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/blk-stat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/partitions/check.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/mq-deadline.c (c07c40c8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/cmdline-parser.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/blk-integrity.c (c07c592c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (c07c6548)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (c07c7668)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In block/blk-wbt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (c07dbd7c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/once.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/generic-radix-tree.c (c07ddd68)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
```
In lib/string_helpers.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/kstrtox.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/math/div64.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/math/reciprocal_div.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/reed_solomon/reed_solomon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/bch.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/dynamic_debug.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/nlattr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/mpi/mpicoder.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/mpi/mpiutil.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/dim/dim.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/digsig.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/sg_split.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-al-fic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-alpine-msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/exynos-combiner.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-tegra.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v2m.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081c4cc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-partition-percpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-crossbar.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-mtk-sysirq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-mtk-cirq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-imx-gpcv2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-aspeed-vic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/irq-meson-gpio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/irqchip/qcom-pdc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/bus/arm-cci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/bus/omap_l3_smx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/bus/ti-sysc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/phy/phy-core-mipi-dphy.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/devicetree.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/pinconf-generic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/pinctrl-rza1.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/pinctrl-rza2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/pinctrl-ocelot.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/berlin/berlin.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084e8d4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/gpio/gpio-mvebu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/gpio/gpio-stmpe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/pci.c (c08834e4)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/slot.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/msi.c (c089f1b8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
```
In drivers/pci/iov.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/ecam.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (c08a4cfc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (c08a5f54)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/endpoint/pci-epc-mem.c:__pci_epc_mem_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_get_order
```
```
In drivers/pci/controller/pcie-rcar.c (c08afb40)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7ef4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/softcursor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/amba-clcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/of_display_timing.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/ipmi/ipmi_dmi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/amba/bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clkdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-divider.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-gate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-mux.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-composite.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-aspeed.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-ast2600.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-highbank.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-hsdk-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-milbeaut.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-npcm7xx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/clk-qoriq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/actions/owl-factor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/berlin/berlin2-avpll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/berlin/berlin2-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/berlin/berlin2-div.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/berlin/bg2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/berlin/bg2q.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/hisilicon/clk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/hisilicon/clkgate-separated.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/hisilicon/clk-hi3620.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/hisilicon/clk-hix5hd2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-busy.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-composite-8m.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-cpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-composite-7ulp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-divider-gate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-fixup-div.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-fixup-mux.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-frac-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-gate-exclusive.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-gate2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-pfd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-pfdv2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-pllv1.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-pllv2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-pllv4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-sccg-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-imx6q.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-imx6sl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-imx6sll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-imx6sx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-imx6ul.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-imx7d.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/imx/clk-imx7ulp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mediatek/clk-mtk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mediatek/clk-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mediatek/clk-gate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mediatek/clk-apmixed.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mediatek/clk-cpumux.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mediatek/reset.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mediatek/clk-mux.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/meson/clk-mpll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/meson/clk-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/meson/meson8b.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mvebu/common.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mvebu/clk-cpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/mvebu/clk-corediv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-rz.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-r8a7740.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-r8a7778.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-r8a7779.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-sh73a0.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-mstp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/renesas/clk-div6.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk-cpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk-half-divider.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk-inverter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk-mmc-phase.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk-muxgrf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/clk-ddr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/rockchip/softrst.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/samsung/clk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/samsung/clk-pll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/samsung/clk-cpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/samsung/clk-exynos-clkout.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-audio-sync.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-divider.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-periph-fixed.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-periph-gate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-pll.c (c090ef24)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-pll.c:_get_table_rate
```
```
In drivers/clk/tegra/clk-pll-out.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-sdmmc-mux.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-super.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-emc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-bpmp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/tegra/clk-utils.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/clk.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/autoidle.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/dpll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/composite.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/divider.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/gate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/mux.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/apll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/clkt_dpll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/clkctrl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/dpll3xxx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/fapll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/interface.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/clk-dra7-atl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/ti/adpll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/versatile/icst.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/versatile/clk-icst.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clk/versatile/clk-sp810.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/of-dma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/amba-pl08x.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/tegra20-apb-dma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/ti/edma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/ti/omap-dma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma/ti/dma-crossbar.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/dove/pmu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/imx/soc-imx8.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/amlogic/meson-clk-measure.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/amlogic/meson-gx-socinfo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/amlogic/meson-mx-socinfo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/qcom/smem_state.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/renesas/renesas-soc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/renesas/rcar-sysc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/renesas/rmobile-sysc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/samsung/exynos-chipid.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/samsung/pm_domains.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/tegra/pmc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/soc/tegra/powergate-bpmp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/imx.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm1.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (c09bfad4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_iova_to_phys
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
```
```
In drivers/iommu/ipmmu-vmsa.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/omap-iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/tegra-gart.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/class.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/attribute_container.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/common.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regmap.c (c09fa8c0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/soc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/platform-msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/misc/vexpress-syscfg.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/sm501.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/t7l66xb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/tc6387xb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/tc6393xb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sd.c (c0a5bc64)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ata/libata-transport.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ata/libahci_platform.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/mtdcore.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/mtdconcat.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/mtdpart.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/mtdchar.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/parsers/cmdlinepart.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/parsers/ofpart.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/mtd_blkdevs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/mtdblock.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/bbt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/raw/nand_base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/raw/nand_bbt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/raw/nand_onfi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/raw/nand_jedec.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/raw/nand_hynix.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/raw/nand_micron.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mtd/nand/raw/nand_bch.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad77e0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
```
```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad9ccc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/net/slip/slhc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/auxdisplay/arm-charlcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/urb.c (c0af75ac)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/phy/phy-ulpi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-mtk-sch.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/musb/musb_host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/musb/musb_gadget.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/gadget/udc/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/usb/roles/class.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/rtc/class.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/rtc/nvmem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/i2c/busses/i2c-s3c2410.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/media/cec/cec-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pps/kapi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/thermal/of-thermal.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-init.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-linear.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/opp/ti-opp-supply.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq-dt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpuidle/governors/menu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpuidle/governors/teo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpuidle/coupled.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpuidle/cpuidle-big_little.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/cpuidle/cpuidle-psci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/sd.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/core/queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/host/mmci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/leds/led-triggers.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/memmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/qcom_scm-32.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/arm_scmi/bus.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/firmware/tegra/bpmp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/sh_cmt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/sh_mtu2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/renesas-ostm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/sh_tmu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/mmio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/dw_apb_timer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/timer-rockchip.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/clocksource/timer-imx-gpt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/device.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/platform.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/dynamic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/fdt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/irq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/of_reserved_mem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/devfreq/governor_simpleondemand.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/memory/samsung/exynos-srom.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/memory/tegra/mc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/vme/vme.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/perf/arm_pmu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/sound_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/sound.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/init.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/control.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/device.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/info.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/sound_oss.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/vmaster.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/jack.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/timer.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/pcm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/pcm_native.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/pcm_lib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/pcm_memory.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/memalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/pcm_dmaengine.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/core/compress_offload.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/soc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/soc-dapm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/soc-pcm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/soc-topology.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/soc-ac97.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/codecs/sgtl5000.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/fsl/fsl_ssi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/fsl/imx-audmux.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In sound/soc/fsl/imx-pcm-fiq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/dev_addr_lists.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (c0d48634)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d908b8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (c0d97ae0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (c0da087c)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (c15b7eac)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/decompress_bunzip2.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/decompress_inflate.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/decompress_unlzma.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/decompress_unxz.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (c0e834dc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
```
```
In lib/idr.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/kobject.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/vsprintf.c (0)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/setup_64.c (c00000000134ad28)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:parse_cache_info
```
```
In arch/powerpc/sysdev/mpic.c (c000000001358ae0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e366c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
```
```
In arch/powerpc/platforms/pseries/msi.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/sched/fair.c (c00000000018f6b4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (c000000000324280)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (c000000000354d80)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (c0000000003739f0)
Location: include/linux/log2.h:22
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
In mm/slub.c (c00000000042a9cc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (c0000000004c96e0)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c0000000004e0e54)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (c00000000051f0a4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (c000000000520574)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (c0000000005a435c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (c00000000064d124)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (c000000000657724)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (c00000000065a318)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (c000000000786e0c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (c0000000007b8d68)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In block/t10-pi.c (c0000000007be09c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (c0000000007bf784)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regmap.c (c0000000009b66f8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (c000000000a04e78)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (c000000000a49e9c)
Location: include/linux/log2.h:22
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
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sd_zbc.c (c000000000a4c870)
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (c000000000ada6ac)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (c000000000d2b2ac)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8c78c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (c000000000d9598c)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (c0000000013c3dbc)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (c000000000ec8d7c)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffe0000ee436)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffe0001b2af4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffe0001d1684)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffe0001de2ae)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffe00023ca40)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffe00028659e)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffe0002940b8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (ffffffe0002b9834)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffe0002ba648)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffe000307ee4)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffe000373878)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffe00037a75c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffe00037c69a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffe00042f378)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffe00044f258)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffe00045097a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffe000451b4a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffe0004527b8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffe000595b1c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c6156)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffe0005edd5e)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/spi/spi-sifive.c (ffffffe00061c408)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/core/urb.c (ffffffe00064365a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/of/base.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7990)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3670)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9a34)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffe00004185a)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffe0008b269a)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810da7c9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811eecc3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8121064f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81224dc2)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff812a1f21)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130aedf)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8131b026)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (ffffffff81347ff9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81349077)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff813a2825)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8141c8db)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81424609)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff814265d8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814e9602)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff8150ceb7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff8150ef06)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8150fc7c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81510cd3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8868)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816e6213)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a45d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8173769e)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_cmd
```
```
In drivers/nvme/host/pci.c (ffffffff81750df7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/usb/core/urb.c (ffffffff817a8b80)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8192982f)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8196ec18)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81975965)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e826)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82906c88)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a4dd05)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810c97d9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811e1a53)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff812033df)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81217f5c)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff81293a01)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fbaf9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130bbc6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (ffffffff81338cd9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81339d57)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff813932b5)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8140d35b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff81415089)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81417058)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814d9b72)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff814fd2e7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff814ff336)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff814fff9c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81500ff3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816964a8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff816c0853)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff816ddedd)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff8171933e)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_cmd
```
```
In drivers/nvme/host/pci.c (ffffffff81730c97)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/usb/core/urb.c (ffffffff8179a590)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff818e35df)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81928708)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f425)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819382e6)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff828fefd6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81a0adf5)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810d6b49)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811eca93)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8120e3ef)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81222b62)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff8129fd31)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81308ccf)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81318af6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (ffffffff81345ac9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81346b47)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff813a0085)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff81418a7b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814207a9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff81422778)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814e5692)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff81508f47)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff8150af96)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff8150bd0c)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff8150cd63)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6d38)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff817133a3)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff8174922d)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81777e2e)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff817e5620)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a9bf)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d93e8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0135)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8ff6)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8291c56b)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81aba0f5)
Location: include/linux/log2.h:22
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
In kernel/sched/fair.c (ffffffff810e2459)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/trace/tracing_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811faf33)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8121d2ff)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81231d42)
Location: include/linux/log2.h:22
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
In mm/slub.c (ffffffff812afe71)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/file.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131a981)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8132a716)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/io_uring.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In fs/verity/enable.c (ffffffff81358da9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/open.c (ffffffff81359e27)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/ext4/inode.c (ffffffff813b40a9)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/fuse/dir.c (ffffffff8142f7eb)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (ffffffff814375ad)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/inode.c (ffffffff814395a8)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In block/blk-mq.c (ffffffff814fe5f2)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_poll_stats_bkt
```
```
In block/mq-deadline.c (ffffffff815226e7)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-integrity.c (ffffffff81524636)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
```
```
In block/t10-pi.c (ffffffff815253ac)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-zoned.c (ffffffff81526443)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
```
In lib/kfifo.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/genalloc.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701438)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/regmap/regmap.c (ffffffff8172e593)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff817646ad)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/scsi/sd.c (ffffffff81791c4e)
Location: include/linux/log2.h:22
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
Location: include/linux/log2.h:22
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
In drivers/usb/core/urb.c (ffffffff817ff880)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8199ceef)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e3048)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9df5)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2d56)
Location: include/linux/log2.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82922fe6)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/xdp/xsk_queue.c (0)
Location: include/linux/log2.h:22
Inline: True
```
```
In lib/flex_proportions.c (ffffffff81ac6545)
Location: include/linux/log2.h:22
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
```
</details>
</li>
</ul>

## Differences
