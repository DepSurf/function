# Function: <code>get_dma_ops</code>

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
In arch/x86/kernel/pci-dma.c (ffffffff81034d2d)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
```
```
In mm/dmapool.c (ffffffff811d9680)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/dma/dmaengine.c (ffffffff814be0fd)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509611)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/virtio_console.c (ffffffff81516a35)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81521ff7)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/dma-mapping.c (ffffffff8155daaf)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/dma-mapping.c:dmam_coherent_release
  - drivers/base/dma-mapping.c:dmam_noncoherent_release
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff815b18b4)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff815cabc0)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_sg_clean
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/ata/libata-sff.c (ffffffff815dd895)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff815e711e)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8160cc16)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff8161794b)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816282a2)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162b2d0)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e53f)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81634ca3)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d3d5)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81641285)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8164428e)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81649763)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff8164e23c)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81655214)
Location: arch/x86/include/asm/dma-mapping.h:31
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In arch/x86/kernel/pci-dma.c (ffffffff81033f0d)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In mm/dmapool.c (ffffffff811f783c)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/dma/dmaengine.c (ffffffff8150dd8d)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f17f)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81512348)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815139d6)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b964)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/virtio_console.c (ffffffff815696ce)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81575d31)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/base/dma-mapping.c (ffffffff815b1cf3)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/dma-mapping.c:dmam_noncoherent_release
  - drivers/base/dma-mapping.c:dmam_coherent_release
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81609c44)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81623cc4)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_sg_clean
```
```
In drivers/ata/libata-sff.c (ffffffff81637617)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff81645982)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8166ceb1)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff81677b46)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a278)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168fd56)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169883a)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169dff1)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a1d95)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4d51)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa1d3)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff816aeb63)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6a0b)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b95ed)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
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
In arch/x86/kernel/pci-dma.c (ffffffff81033b3d)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In mm/dmapool.c (ffffffff812081ec)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/dma/dmaengine.c (ffffffff81539eed)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b2d9)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d75f)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8153e6e7)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8153fdf6)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81588126)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/virtio_console.c (ffffffff81595e0e)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a23c1)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/base/dma-mapping.c (ffffffff815e11e3)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/dma-mapping.c:dmam_noncoherent_release
  - drivers/base/dma-mapping.c:dmam_coherent_release
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81639524)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81654844)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_sg_clean
```
```
In drivers/ata/libata-sff.c (ffffffff816686b7)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff8167684e)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8169abb1)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff816a5826)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b83e4)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bde06)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c6d6a)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cc130)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d0a15)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2e51)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d8323)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff816dcd03)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e4cdd)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e786d)
Location: arch/x86/include/asm/dma-mapping.h:30
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In mm/dmapool.c (ffffffff812138e0)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d2458)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2be8)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/dma/dmaengine.c (ffffffff8154d741)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154eb62)
Location: include/linux/dma-mapping.h:198
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81551411)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81552427)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81553bdd)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c589)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/virtio_console.c (ffffffff815a9bf3)
Location: include/linux/dma-mapping.h:198
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b53dd)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/base/dma-mapping.c (ffffffff815f5dae)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/dma-mapping.c:dmam_release
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8164e08c)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81668e52)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/ata/libata-sff.c (ffffffff8167ce67)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff8168af4f)
Location: include/linux/dma-mapping.h:198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816affa3)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff816babab)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c5ff7)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cc6aa)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d1d70)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816db53c)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816e0304)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e088d)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e509d)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7559)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ec83f)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff816f1100)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f8c33)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fbb18)
Location: include/linux/dma-mapping.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In mm/dmapool.c (ffffffff8122e460)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81512898)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512fe8)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/dma/dmaengine.c (ffffffff815b0db4)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b2312)
Location: include/linux/dma-mapping.h:201
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4c33)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815b5d18)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815b755b)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8160187c)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/virtio_console.c (ffffffff8161051c)
Location: include/linux/dma-mapping.h:201
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c3bf)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/base/dma-mapping.c (ffffffff8165dd6e)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/dma-mapping.c:dmam_release
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816b7380)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff816d24ed)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/ata/libata-sff.c (ffffffff816e6585)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff816f48bf)
Location: include/linux/dma-mapping.h:201
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8171b519)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff8172656b)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/platform.c (ffffffff817322f7)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738c2b)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173e3f0)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81747c6c)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8174cae4)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d10d)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817518c7)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753d76)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8175902f)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff8175d318)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81765802)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81768695)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772c92)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In kernel/dma/mapping.c (ffffffff8110c7ae)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/dma/mapping.c:dmam_alloc_coherent
  - kernel/dma/mapping.c:dmam_release
```
```
In mm/dmapool.c (ffffffff812512a4)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81548398)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549524)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff815e9201)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea772)
Location: include/linux/dma-mapping.h:201
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ecf00)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815ee100)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815efa8b)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ab36)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/virtio_console.c (ffffffff8164a7a1)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8165608f)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816f3678)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8170ebde)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/ata/libata-sff.c (ffffffff81722e65)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff8173297d)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8175a2c8)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff8176536f)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771c18)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778c7b)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177ae90)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177ed96)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81788458)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d3e9)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d93c)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8179138c)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817943c6)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8179986c)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff8179dd39)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a5b49)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a95f2)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3231)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcdcd)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd53e)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
```
```
In net/core/page_pool.c (ffffffff818bd72e)
Location: include/linux/dma-mapping.h:201
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff81118025)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fc26)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff816036c0)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81605796)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658dac)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81674418)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170af07)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81716062)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81731072)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff8175539b)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8177e848)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179ae98)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a10b5)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a553e)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cf5b5)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da8d8)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In net/core/page_pool.c (ffffffff818e4b0a)
Location: include/linux/dma-mapping.h:266
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff811223bd)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffffffff812c3528)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8158fef3)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff81635ef3)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8163a97c)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e2ae)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a99b4)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81746ad1)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81751846)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8176c832)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817914a7)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817bcdf0)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817da020)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e000e)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4764)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180fa31)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b001)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In net/core/page_pool.c (ffffffff81934231)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff8112e74c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffffffff812d5557)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1f13)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff81657c13)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8165ce3c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b087e)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cc6f4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176ac21)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81775ac6)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff817908a2)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817b50a7)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817ed7cd)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180b104)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81810efe)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81815624)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81840e7e)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bd08)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f48eb)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81966e64)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff8113d045)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b4e9)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff81707353)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a8c6)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763c50)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81781078)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_unmap_memory
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
```
```
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a22b)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_unmap_dma_buf
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_map_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182c85d)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff818389df)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81854f65)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/ata/libata-core.c:ata_sg_setup
```
```
In drivers/spi/spi.c (ffffffff8187bc92)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff818bce95)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818da78c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e1725)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e5846)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_fill_host_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81911b7c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191eb27)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819caa12)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81a3a8ea)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9aba)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
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
In kernel/dma/mapping.c (ffffffff811374f5)
Location: include/linux/dma-map-ops.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_free_noncoherent
  - kernel/dma/mapping.c:dma_alloc_noncoherent
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/ops_helpers.c (ffffffff81139c85)
Location: include/linux/dma-map-ops.h:77
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9f6b)
Location: include/linux/dma-map-ops.h:77
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/mapping.c (ffffffff811382a5)
Location: include/linux/dma-map-ops.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ada5)
Location: include/linux/dma-map-ops.h:77
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aef7b)
Location: include/linux/dma-map-ops.h:77
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/mapping.c (ffffffff8115b045)
Location: include/linux/dma-map-ops.h:78
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/ops_helpers.c (ffffffff8115dcd5)
Location: include/linux/dma-map-ops.h:78
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d576)
Location: include/linux/dma-map-ops.h:78
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/mapping.c (ffffffff81184955)
Location: include/linux/dma-map-ops.h:78
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/ops_helpers.c (ffffffff81187ca5)
Location: include/linux/dma-map-ops.h:78
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd6a6)
Location: include/linux/dma-map-ops.h:78
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/mapping.c (ffffffff811bff85)
Location: include/linux/dma-map-ops.h:89
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_pci_p2pdma_supported
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/ops_helpers.c (ffffffff811c39a5)
Location: include/linux/dma-map-ops.h:89
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c0ea)
Location: include/linux/dma-map-ops.h:89
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In kernel/dma/mapping.c (ffffffff811d2a65)
Location: include/linux/dma-map-ops.h:90
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_pci_p2pdma_supported
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/ops_helpers.c (ffffffff811d64f5)
Location: include/linux/dma-map-ops.h:90
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea2aa)
Location: include/linux/dma-map-ops.h:90
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In kernel/dma/mapping.c (ffffffff811e76e5)
Location: include/linux/dma-map-ops.h:91
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - kernel/dma/mapping.c:dma_addressing_limited
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_pci_p2pdma_supported
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_free_pages
  - kernel/dma/mapping.c:__dma_alloc_pages
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb525)
Location: include/linux/dma-map-ops.h:91
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea0516)
Location: include/linux/dma-map-ops.h:91
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In kernel/dma/mapping.c (ffff800010193a04)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffff80001037a930)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e428)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffff8000107fce5c)
Location: include/linux/dma-mapping.h:261
Inline: True
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804810)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_free
```
```
In drivers/dma/mv_xor.c (ffff800010807414)
Location: include/linux/dma-mapping.h:261
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816430)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
```
```
In drivers/virtio/virtio_ring.c (ffff800010822fe0)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bd3c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/amba-pl011.c (ffff8000108962c0)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (ffff80001089c870)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a39e4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb158)
Location: include/linux/dma-mapping.h:261
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d80dc)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c740)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffff80001097a260)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffff80001099a4f0)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffff8000109c87b8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3664)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e655c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/usb/core/hcd.c (ffff800010a1c8f8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a417fc)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a49f78)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e7b8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7f89c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b9b4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/mmc/host/mmci.c (ffff800010b458f8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (ffff800010b483e4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
```
```
In drivers/firmware/qcom_scm-64.c (ffff800010b4f8a8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/linux/dma-mapping.h:261
Inline: True
```
```
In net/core/page_pool.c (ffff800010c0c900)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/arm/mm/dma-mapping.c (c031b5e4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_dma_sync_sg_for_device
  - arch/arm/mm/dma-mapping.c:arm_dma_sync_sg_for_cpu
  - arch/arm/mm/dma-mapping.c:arm_dma_unmap_sg
  - arch/arm/mm/dma-mapping.c:arm_dma_map_sg
```
```
In kernel/dma/mapping.c (c03e0d4c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (c0565e7c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7ca4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (c091f528)
Location: include/linux/dma-mapping.h:261
Inline: True
```
```
In drivers/dma/mv_xor.c (c0925134)
Location: include/linux/dma-mapping.h:261
Inline: True
```
```
In drivers/virtio/virtio_ring.c (c0940b7c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (c098970c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/amba-pl011.c (c099246c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (c09975dc)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/tty/serial/msm_serial.c (c099cc80)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/iommu/io-pgtable-arm.c (c09bfd60)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_sync_pte
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pages
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c4170)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:_omap_iommu_detach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_detach
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopte_alloc_large
  - drivers/iommu/omap-iommu.c:iopte_alloc_page
  - drivers/iommu/omap-iommu.c:iopte_alloc
  - drivers/iommu/omap-iommu.c:iopte_alloc
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c66b8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/iommu/tegra-smmu.c (c09c8a7c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_unmap
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde
  - drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09cae5c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
```
```
In drivers/dma-buf/udmabuf.c (c0a422a8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (c0a4da88)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (c0a6a754)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/mtd/nand/raw/omap2.c (c0aac554)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
```
```
In drivers/spi/spi.c (c0ab23ec)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac9614)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad6e30)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
```
In drivers/usb/core/hcd.c (c0af58b8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c0b13fbc)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1c394)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b20878)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (c0b52c78)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5dde0)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/gadget/udc/core.c (c0b73e48)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9a978)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_callback
```
```
In drivers/mmc/host/mmci.c (c0c1f7f0)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:mmci_dma_unmap
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c21938)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
```
```
In drivers/mmc/host/sdhci.c (c0c24c68)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_post_req
  - drivers/mmc/host/sdhci.c:sdhci_finish_data
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c300)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_post_req
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_pre_dma_transfer
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_dma_callback
```
```
In drivers/mmc/host/cqhci.c (c0c3105c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_post_req
```
```
In drivers/firmware/qcom_scm-32.c (c0c36274)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c432ec)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/firmware/tegra/ivc.c:tegra_ivc_cleanup
  - drivers/firmware/tegra/ivc.c:tegra_ivc_cleanup
  - drivers/firmware/tegra/ivc.c:tegra_ivc_notified
  - drivers/firmware/tegra/ivc.c:tegra_ivc_notified
  - drivers/firmware/tegra/ivc.c:tegra_ivc_notified
  - drivers/firmware/tegra/ivc.c:tegra_ivc_reset
  - drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance
  - drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance
  - drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c05c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_dma_unmap_single
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_dma_unmap_single
```
```
In drivers/remoteproc/remoteproc_core.c (c0c64058)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (c0d24ae4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d25c8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_dma_dev_setup
```
```
In kernel/dma/mapping.c (c0000000001f3b90)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_cache_sync
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (c00000000046f364)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (c0000000008c9218)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/virtio/virtio_ring.c (c0000000008d08cc)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (c00000000093479c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c00000000096911c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
```
```
In drivers/dma-buf/udmabuf.c (c000000000a2580c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (c000000000a348e0)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (c000000000a5da88)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (c000000000a8a1b4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (c000000000ad7d40)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c000000000b02820)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b0feb4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b16340)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (c000000000b583d8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67928)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d30c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (c000000000cf7ad4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffe000125e3c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffffffe000251da6)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8b96)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffe0005173e2)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/virtio/virtio_ring.c (ffffffe000519912)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe00055565a)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d7682)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffe0005e1396)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffe0005faeb8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffe000618c06)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffe000641624)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065d82e)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000666e3c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066b156)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006962d2)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0722)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b1a4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
```
```
In net/core/page_pool.c (ffffffe0007898b2)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff81126d2c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffffffff812cdb37)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a56d3)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff8161dab3)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81622cdc)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816762ee)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692144)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f311)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8172a1b6)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/nvme/host/pci.c (ffffffff8174e653)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
```
In drivers/ata/libata-core.c (ffffffff817559e2)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff81779b87)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817a5bad)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c34e4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817c92de)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cda04)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f922e)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895c1b)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81906e34)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff8111978c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffffffff812be9a7)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594873)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff816121a3)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161732c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816553ce)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166fb34)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8741)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817035d6)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/nvme/host/pci.c (ffffffff8172e4f3)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
```
In drivers/ata/libata-core.c (ffffffff81735882)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff81759937)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817980dd)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817be3ce)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9258)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In net/core/page_pool.c (ffffffff818c0c44)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff81124c1c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffffffff812cb947)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5c63)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff8164ba53)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81650c7c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a46be)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c03b4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175e0e1)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81768f86)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81785722)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817a9f27)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817e264d)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817fff84)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81805d7e)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180a4a4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81835cfe)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840b88)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81869000)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion
```
```
In net/core/page_pool.c (ffffffff81957e64)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In kernel/dma/mapping.c (ffffffff8113125c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_get_merge_boundary
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_supported
  - kernel/dma/mapping.c:dma_free_attrs
  - kernel/dma/mapping.c:dma_alloc_attrs
  - kernel/dma/mapping.c:dma_get_required_mask
  - kernel/dma/mapping.c:dma_mmap_attrs
  - kernel/dma/mapping.c:dma_can_mmap
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
```
In mm/hmm.c (ffffffff812dc6a7)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c0063)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff81665ff3)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8166b30c)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816beb76)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816da984)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779741)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817846f6)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8179f552)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817c3db7)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817fd39d)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181a094)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8181fe8e)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818245b4)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81850034)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b058)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8190637b)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81979f52)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
</ul>

## Differences
