# Function: <code>get_arch_dma_ops</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81213a2b)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d253c)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2c71)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/dma/dmaengine.c (ffffffff8154d856)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154eb83)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815514ab)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8155278e)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81553c91)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c697)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/virtio_console.c (ffffffff815a9c89)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b54c6)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/base/dma-mapping.c (ffffffff815f5e4a)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/dma-mapping.c:dmam_release
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8164e0ba)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81668f19)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/ata/libata-sff.c (ffffffff8167cf7a)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff8168af8b)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816b0269)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/core/buffer.c (ffffffff816babf4)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c6244)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cca86)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d1f94)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/host/ehci-hcd.c (ffffffff816db8fc)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816e0442)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e0ad8)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e50e6)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e770c)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ec87d)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff816f135f)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f9240)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/host/xhci-ring.c (ffffffff816fbbf4)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
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
In mm/dmapool.c (ffffffff8122e5ae)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815129a3)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81513074)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/dma/dmaengine.c (ffffffff815b0ed2)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b2339)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4cfd)
Location: arch/x86/include/asm/dma-mapping.h:29
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
In drivers/virtio/virtio_pci_modern.c (ffffffff815b5fcd)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815b7620)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8160199a)
Location: arch/x86/include/asm/dma-mapping.h:29
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
In drivers/char/virtio_console.c (ffffffff816105e9)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c4dc)
Location: arch/x86/include/asm/dma-mapping.h:29
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
In drivers/base/dma-mapping.c (ffffffff8165de0d)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/dma-mapping.c:dmam_release
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816b73ac)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff816d257d)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/ata/libata-sff.c (ffffffff816e66ba)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff816f48fd)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8171b7b6)
Location: arch/x86/include/asm/dma-mapping.h:29
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
In drivers/usb/core/buffer.c (ffffffff817265b7)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/platform.c (ffffffff8173256d)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81739029)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173e616)
Location: arch/x86/include/asm/dma-mapping.h:29
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174802f)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8174cc54)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d35e)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81751913)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753f2c)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81759070)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff8175d5a0)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81765d50)
Location: arch/x86/include/asm/dma-mapping.h:29
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
In drivers/usb/host/xhci-ring.c (ffffffff81768768)
Location: arch/x86/include/asm/dma-mapping.h:29
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772d51)
Location: arch/x86/include/asm/dma-mapping.h:29
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
In kernel/dma/mapping.c (ffffffff8110c85f)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/dma/mapping.c:dmam_alloc_coherent
  - kernel/dma/mapping.c:dmam_release
```
```
In mm/dmapool.c (ffffffff81251406)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8154844a)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815495cd)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff815e9212)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea799)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ecfb7)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/virtio/virtio_pci_modern.c (ffffffff815ee24f)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815efbd8)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ac82)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/char/virtio_console.c (ffffffff8164a80c)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8165617a)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/scsi/scsi_lib_dma.c (ffffffff816f36ab)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8170ec21)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/ata/libata-sff.c (ffffffff81722f3c)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/spi/spi.c (ffffffff817329bf)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8175a587)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/core/buffer.c (ffffffff817653b9)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771ef4)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8177904f)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177af49)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177ee9c)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178883c)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d558)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178db48)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817913df)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817945d9)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817998ad)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci.c (ffffffff8179de8b)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a637a)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/host/xhci-ring.c (ffffffff817a99db)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b32fe)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dd0db)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd675)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
```
```
In net/core/page_pool.c (ffffffff818bd7a0)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In kernel/dma/mapping.c (ffffffff81118054)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fc9d)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff816036d1)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff816057b4)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658e68)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8167460e)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170af64)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8171607a)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8173108a)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817553b3)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8177eaba)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/dwc2/hcd.c (ffffffff8179b0bc)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a1179)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a5647)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In drivers/usb/host/xhci-ring.c (ffffffff817cf946)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817daa67)
Location: arch/x86/include/asm/dma-mapping.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In net/core/page_pool.c (ffffffff818e4b4f)
Location: arch/x86/include/asm/dma-mapping.h:28
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
In kernel/dma/mapping.c (ffffffff811223d8)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In mm/hmm.c (ffffffff812c3578)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8158ff5d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff81635ff4)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8163a9ce)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e2d7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a99f5)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81746add)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81751852)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8176c8c3)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817914b3)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817bd03a)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/dwc2/hcd.c (ffffffff817da244)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e0077)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4867)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/host/xhci-ring.c (ffffffff8180fdcd)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b01a)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In net/core/page_pool.c (ffffffff8193423e)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In kernel/dma/mapping.c (ffffffff8112e768)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In mm/hmm.c (ffffffff812d55a7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1f7d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff81657d14)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8165ce8e)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b08a7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cc735)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176ac2d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81775ad2)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81790933)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817b50b3)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817edaa1)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/dwc2/hcd.c (ffffffff8180b137)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81810f67)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81815727)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/host/xhci-ring.c (ffffffff81840f83)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bd21)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f48eb)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81966e71)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In kernel/dma/mapping.c (ffffffff8113d068)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b582)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff81707454)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a920)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763c87)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8178109e)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_unmap_memory
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
```
```
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a246)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_unmap_dma_buf
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_map_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182c870)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff818389f2)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81854f82)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/ata/libata-core.c:ata_sg_setup
```
```
In drivers/spi/spi.c (ffffffff8187bca5)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff818bcfc3)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/dwc2/hcd.c (ffffffff818da7ad)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e178d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e5957)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/host/xhci-ring.c (ffffffff81911d4c)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191eb3d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819caa1f)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81a3a901)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9adb)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In kernel/dma/mapping.c (ffffffff81137518)
Location: arch/x86/include/asm/dma-mapping.h:19
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
In kernel/dma/ops_helpers.c (ffffffff81139c99)
Location: arch/x86/include/asm/dma-mapping.h:19
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9f78)
Location: arch/x86/include/asm/dma-mapping.h:19
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
In kernel/dma/mapping.c (ffffffff811382c8)
Location: arch/x86/include/asm/dma-mapping.h:19
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
In kernel/dma/ops_helpers.c (ffffffff8113adb9)
Location: arch/x86/include/asm/dma-mapping.h:19
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aef88)
Location: arch/x86/include/asm/dma-mapping.h:19
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
In kernel/dma/mapping.c (ffffffff8115b068)
Location: arch/x86/include/asm/dma-mapping.h:19
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
In kernel/dma/ops_helpers.c (ffffffff8115dce9)
Location: arch/x86/include/asm/dma-mapping.h:19
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d583)
Location: arch/x86/include/asm/dma-mapping.h:19
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
In kernel/dma/mapping.c (ffffffff8118497e)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/ops_helpers.c (ffffffff81187cb9)
Location: arch/x86/include/asm/dma-mapping.h:7
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd6b3)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/mapping.c (ffffffff811bffae)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/ops_helpers.c (ffffffff811c39b9)
Location: arch/x86/include/asm/dma-mapping.h:7
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c0f6)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/mapping.c (ffffffff811d2a8e)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/ops_helpers.c (ffffffff811d6509)
Location: arch/x86/include/asm/dma-mapping.h:7
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea2b6)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/mapping.c (ffffffff811e770e)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/ops_helpers.c (ffffffff811eb539)
Location: arch/x86/include/asm/dma-mapping.h:7
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea0522)
Location: arch/x86/include/asm/dma-mapping.h:7
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
In kernel/dma/mapping.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/dma/bcm2835-dma.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/tty/serial/imx.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/mmc/host/mmci.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/firmware/qcom_scm-64.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
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
In arch/arm/mm/dma-mapping.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In kernel/dma/mapping.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/tty/serial/imx.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/iommu/omap-iommu.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/usb/gadget/udc/core.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/mmc/host/mmci.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/mmc/host/cqhci.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/firmware/qcom_scm-32.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/firmware/tegra/ivc.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
Inline: True
```
```
In net/core/page_pool.c (0)
Location: arch/arm/include/asm/dma-mapping.h:19
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
In arch/powerpc/platforms/powernv/pci-ioda.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In kernel/dma/mapping.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
```
```
In net/core/page_pool.c (0)
Location: arch/powerpc/include/asm/dma-mapping.h:8
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In drivers/mmc/host/mmc_spi.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/asm-generic/dma-mapping.h:5
Inline: True
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
In kernel/dma/mapping.c (ffffffff81126d48)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In mm/hmm.c (ffffffff812cdb87)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a573d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff8161dbb4)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81622d2e)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81676317)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692185)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f31d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8172a1c2)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/nvme/host/pci.c (ffffffff8174e696)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/ata/libata-core.c (ffffffff81755a73)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff81779b93)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817a5e81)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/dwc2/hcd.c (ffffffff817c3517)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817c9347)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cdb07)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/host/xhci-ring.c (ffffffff817f9333)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895c1b)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81906e41)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In kernel/dma/mapping.c (ffffffff811197a8)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In mm/hmm.c (ffffffff812be9f7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815948dd)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff816122a4)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161737e)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816553f7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166fb75)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f874d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817035e2)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/nvme/host/pci.c (ffffffff8172e536)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/ata/libata-core.c (ffffffff81735913)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff81759943)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817983b1)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/host/xhci-ring.c (ffffffff817be4d3)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9271)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In net/core/page_pool.c (ffffffff818c0c51)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In kernel/dma/mapping.c (ffffffff81124c38)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In mm/hmm.c (ffffffff812cb997)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5ccd)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff8164bb54)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81650cce)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a46e7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c03f5)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175e0ed)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81768f92)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff817857b3)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817a9f33)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817e2921)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/dwc2/hcd.c (ffffffff817fffb7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81805de7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180a5a7)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/host/xhci-ring.c (ffffffff81835e03)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840ba1)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff8186902d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion
```
```
In net/core/page_pool.c (ffffffff81957e71)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In kernel/dma/mapping.c (ffffffff81131278)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In mm/hmm.c (ffffffff812dc6f7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c00cd)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/dmaengine.c (ffffffff816660f4)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8166b35e)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816beb9f)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816da9c5)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8177974d)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81784702)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8179f5fc)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817c3dc3)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817fd671)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/dwc2/hcd.c (ffffffff8181a0c7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8181fef7)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818246b7)
Location: arch/x86/include/asm/dma-mapping.h:21
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
In drivers/usb/host/xhci-ring.c (ffffffff81850152)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b071)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8190637b)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In net/core/page_pool.c (ffffffff81979f5f)
Location: arch/x86/include/asm/dma-mapping.h:21
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
</ul>

## Differences
