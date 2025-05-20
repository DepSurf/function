# Function: <code>pfn_to_gfn</code>

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
In arch/x86/xen/smp.c (ffffffff8102ba0e)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff814c5628)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant
```
```
In drivers/xen/balloon.c (ffffffff814c65c4)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff814c7531)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fa4a32)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff814cab3c)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc387)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fa4cb8)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff814d0d25)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff814d27d0)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4255)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d6f2e)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814fef51)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81574cc7)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff815fb1ec)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp.c (ffffffff8102ab8d)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81516a06)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff81516ce5)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81517db5)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fd0ff1)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151ba50)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151cf0f)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fd127f)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81521a28)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81523504)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525082)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527cd9)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154f766)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff815cc714)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8165b12a)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp.c (ffffffff8102ad1d)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81542e3d)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff8154315f)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815440a5)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8200e969)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547f20)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815493df)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8200ec0f)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8154def8)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8154f9dd)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551542)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff8155424a)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157bfe6)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff815f92e1)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81688e46)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff810296eb)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81556ced)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff81556fe9)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81557f1d)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff820f0419)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155ba20)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d356)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff820f06d9)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81562388)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81564114)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81565d0f)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568dca)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590252)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff8160d45c)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8169e689)
Location: arch/x86/include/asm/xen/page.h:218
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102990a)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff815bad1d)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff815baff5)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815bc098)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff826f9c23)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bfd40)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1656)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff826f9ee3)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815c6688)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff815c8264)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815c9eaf)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff815ccf7a)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4d52)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81675cdc)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81709829)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102a348)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff815f32c7)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff815f36ff)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815f45a2)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82723fb7)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f841a)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f976c)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82724262)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815fee8f)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81600ade)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602acf)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff816056a7)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162dde2)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff816b122c)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81748319)
Location: arch/x86/include/asm/xen/page.h:225
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102aa2b)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff8160e327)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e75b)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8160f402)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828dc190)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8161377a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8161482c)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828dc43b)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81619f5f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8161bbae)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161d7ef)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81620787)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164bff2)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff816d156c)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8176c3d9)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102c86c)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8164203a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816424e4)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff816431fd)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828f6a89)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81647594)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648508)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828f6d2a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8164dd2f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8164f838)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650a1f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff81653d0a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680de4)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff8170cffc)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817aa1fa)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102d13c)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816645fa)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81664aad)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8166579d)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828ffae0)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669a34)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166a9a8)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828ffd81)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167020f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81671de8)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81672f9f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff816762aa)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3494)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff817312fc)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817cdc5a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102f0c9)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81713b9a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81714672)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81714e5d)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82d16e89)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff817197b8)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ab22)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82d1707d)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8172072b)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff817224b8)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817236ef)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726e1a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817559e4)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff817edac0)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8189816c)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102fed9)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81730a8a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730d52)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81731a4d)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83004a79)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736a06)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737c92)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83004c5d)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8173d68b)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff8173f118)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817403a5)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff8174337a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770c54)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff818023f0)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff818a6531)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff81030958)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff8171461a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817148de)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8171553c)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8320f52e)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a4f3)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b6b2)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8320f7bf)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8172123f)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81722b5c)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723e5a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726d7a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754704)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff817e87f4)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81889941)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff81035828)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff817913ba)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8179172b)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8179254c)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff832f84d5)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798c22)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a168)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff832f8766)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817a005f)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff817a19ac)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2ce6)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a5daa)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d7dc7)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81874d6e)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8191c44e)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8103b642)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff818c9ab8)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff818ca213)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff818cad91)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff834b0d13)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1e3d)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3c92)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff834b0ff7)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff818d9b27)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff818db9e6)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dcf66)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff818dfd2b)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81915fed)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd032)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81a719dc)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff81043e12)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a1a9c8)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a1add3)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81a1bf53)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83eeab1a)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23fad)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a25e8c)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeaf16)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a2c617)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a2eb26)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a303a6)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a3419b)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a35210)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a7170d)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81b326f2)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c0771c)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff81043f26)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a63b78)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a63f83)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81a650f3)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8371050a)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d4e4)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f43c)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710926)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a75dc7)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a782e6)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79bb6)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7dbbb)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7ec20)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abbfbd)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81b85bae)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c6ce25)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8104a455)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81ab63b8)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81ab67c3)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81ab7953)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83943e8a)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf554)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac153c)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff839442a6)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81ac7fb7)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81aca606)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc023)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad005b)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1190)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0ecda)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd9abe)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81d21777)
Location: arch/x86/include/asm/xen/page.h:243
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/arm/xen/enlighten.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/xen/arm/page.h:47
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/xen/arm/page.h:47
Inline: True
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d29c)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8162a46a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a91d)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8162b33d)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828e72fd)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f8a4)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630818)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828e759e)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816362cf)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81637ea8)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81638c8f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163bf9a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668ef4)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff816f71dc)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8179287a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d0fc)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8165843a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816588ed)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff816595dd)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828fae03)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d874)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165e7e8)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828fb0a4)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8166404f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81665c28)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81666ddf)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a0ea)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816972d4)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff817247bc)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817c2ada)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In arch/x86/xen/smp_pv.c (ffffffff8102deec)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81672a3a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672f01)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81673bdd)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82900b34)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677e84)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81679328)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82900dd5)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167e60f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff816801d8)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8168138f)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff816846aa)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1884)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81740470)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817dcd9a)
Location: arch/x86/include/asm/xen/page.h:252
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
</ul>

## Differences
