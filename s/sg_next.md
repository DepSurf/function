# Function: <code>sg_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813f9d50)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_nents
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_alloc_table_from_pages
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - crypto/scatterwalk.c:scatterwalk_bytes_sglen
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/ahash.c:crypto_hash_walk_done
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff813f9d50-ffffffff813f9d75: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814418b7)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81440d90-ffffffff81440db5: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145eac6)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/scompress.c:crypto_scomp_sg_free
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
  - crypto/xts.c:post_crypt
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8145dfb0-ffffffff8145dfd5: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463d9d)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
  - crypto/xts.c:post_crypt
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff814632b0-ffffffff814632d5: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f255)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
  - crypto/xts.c:post_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8148f1c0-ffffffff8148f1e5: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4072)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/swiotlb.c:swiotlb_sync_sg_for_device
  - kernel/dma/swiotlb.c:swiotlb_sync_sg_for_cpu
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
  - crypto/xts.c:post_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff814c3df0-ffffffff814c3e0f: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8772)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff814d84e0-ffffffff814d84ff: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815046e5)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff815042f0-ffffffff8150430f: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522675)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81522300-ffffffff8152231f: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81586626)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/virt.c:dma_virt_map_sg
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_bvec_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/intel/iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel/iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel/iommu.c:bounce_map_sg
  - drivers/iommu/intel/iommu.c:bounce_map_sg
  - drivers/iommu/intel/iommu.c:bounce_map_sg
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:intel_unmap_sg
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_fill_sg_dumb
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81585660-ffffffff8158567f: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3217)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_bvec_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:dup_sg_table
  - drivers/dma-buf/heaps/system_heap.c:dup_sg_table
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_fill_sg_dumb
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff815a2760-ffffffff815a277f: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa5d7)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff815a9680-ffffffff815a96a1: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613867)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81612800-ffffffff81612821: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dee86)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff816dec90-ffffffff816decc1: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf046)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gmch_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff817cee30-ffffffff817cee61: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180d4f6)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gmch_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff8180d2e0-ffffffff8180d311: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff818531a6)
Location: lib/scatterlist.c:25
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:__blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gmch_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/gpu/drm/drm_prime.c:drm_prime_get_contiguous_size
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81852f90-ffffffff81852fc1: sg_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c310)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - lib/sg_split.c:sg_split
  - lib/sg_split.c:sg_split
  - lib/sg_split.c:sg_split
  - lib/sg_split.c:sg_calculate_split
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg
  - drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg
  - drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libahci.c:ahci_qc_prep
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/block.c:mmc_blk_data_prep
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_validate_data
```
**Symbols:**

```
ffff80001062bee8-ffff80001062bf10: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2cd4)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_sync_sg_for_device
  - arch/arm/mm/dma-mapping.c:arm_iommu_sync_sg_for_cpu
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_sg
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_sg
  - arch/arm/mm/dma-mapping.c:__iommu_map_sg
  - arch/arm/mm/dma-mapping.c:__iommu_map_sg
  - arch/arm/mm/dma-mapping.c:__iommu_map_sg
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:arm_dma_sync_sg_for_device
  - arch/arm/mm/dma-mapping.c:arm_dma_sync_sg_for_cpu
  - arch/arm/mm/dma-mapping.c:arm_dma_unmap_sg
  - arch/arm/mm/dma-mapping.c:arm_dma_map_sg
  - arch/arm/mm/dma-mapping.c:arm_dma_map_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - lib/sg_split.c:sg_split
  - lib/sg_split.c:sg_split
  - lib/sg_split.c:sg_calculate_split
  - lib/sg_split.c:sg_calculate_split
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg
  - drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_prep_slave_sg
  - drivers/dma/ti/edma.c:edma_prep_slave_sg
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libahci.c:ahci_qc_prep
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/block.c:mmc_blk_data_prep
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_validate_data
  - drivers/mmc/host/sdhci.c:sdhci_finish_data
  - drivers/mmc/host/sdhci.c:sdhci_finish_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/cqhci.c:cqhci_request
```
**Symbols:**

```
c07d2928-c07d295c: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007ced0c)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/powerpc/kernel/iommu.c:ppc_iommu_unmap_sg
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/virt.c:dma_virt_map_sg
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
c0000000007ce660-c0000000007ce698: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c54e)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/block.c:mmc_blk_data_prep
```
**Symbols:**

```
ffffffe00045c104-ffffffe00045c12e: sg_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151ac55)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8151a8e0-ffffffff8151a8ff: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150af45)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/sr.c:sr_init_command
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8150abd0-ffffffff8150abef: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516ce5)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81516970-ffffffff8151698f: sg_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_next(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530475)
Location: lib/scatterlist.c:23
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_nents
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/sr.c:sr_init_command
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep
  - drivers/ata/libata-sff.c:ata_bmdma_qc_prep
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/mmc/core/core.c:mmc_mrq_prep
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81530100-ffffffff8153011f: sg_next (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
